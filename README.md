 <h1>Desafio Pessoal, configuração de Site Estático no AWS S3 </h1>
  <h2>Documentação </h2>

  
<h3>Análise do Negócio:</h3>
<p>
O negócio analisado se refere à oferta de serviços no campo do desenvolvimento de software e gerenciamento de infraestrutura em nuvem. O objetivo central desses serviços é atender a diversas demandas tecnológicas, com foco em fornecer soluções adaptadas às necessidades corporativas específicas.
Esses serviços incluem o planejamento e a estruturação de sistemas complexos, com base em competências e experiência técnica que garantem arquiteturas de software bem projetadas e escaláveis. Isso assegura que o sistema possa evoluir conforme o crescimento e as mudanças nas demandas do negócio.
O gerenciamento de infraestrutura em nuvem também está no escopo do negócio, envolvendo a implementação e administração de soluções que oferecem suporte à escalabilidade e segurança necessárias para as operações da empresa. Essa abordagem garante que a infraestrutura possa ser ajustada para atender a requisitos em constante mudança, mantendo a eficiência e a proteção dos dados.
</p>

<p>
<h2>Requisitos:</h2>
<p>
O projeto consiste em um site estático global para exibir o nome do titular e suas principais competências e serviços de forma clara e profissional. Incluirá uma seção de apresentação pessoal e uma detalhada sobre habilidades e áreas de atuação, permitindo que os visitantes compreendam a experiência do titular. Métodos de contato direto, como links para redes profissionais, facilitarão a comunicação e atrairão clientes em potencial e recrutadores.
O "Portfólio de Ana Santana" será um portfólio pessoal com design limpo e responsivo, destacando o nome e especializações da desenvolvedora. As seções "Sobre mim", "Habilidades" e "Contato" organizarão informações de forma clara, utilizando um reset básico para garantir legibilidade e cores contrastantes, como cinza claro, cinza escuro e azul. A seção de habilidades listará competências técnicas, e o rodapé terá uma declaração de direitos autorais. As ferramentas permitirão interatividade básica, logando no console ao carregar a página.
O site será hospedado na AWS, seguindo as melhores práticas de segurança, com custo estimado de $2 por dia, oferecendo alta disponibilidade e acesso eficiente na América do Norte e Europa. Após dois dias e a documentação dos requisitos, a estrutura em nuvem será finalizada, mantendo apenas as documentações em repositórios para aprendizado e portfólios.
</p>


<p>
            
        
</p>

<p>
   <h3>Testes Funcionais</h3>
    <p>Objetivo: Verificar se o site estático funciona conforme o esperado, garantindo que todos os recursos estejam operacionais e que o desempenho do site seja satisfatório. Isso inclui a avaliação dos tempos de carregamento, escalabilidade, segurança, e latência, assegurando uma experiência de usuário consistente e de alta qualidade globalmente.</p>                
</p>

<p>
                        
<p>

</p>
 <h3>Plano de Testes</h3>
  <p>

</p>
 <h3>Testes de Latência:</h3>
  <p>
<p > 1-Avaliar o tempo de resposta do site para visitantes das Américas e da Europa</p>

<p > 2- Garantir que o site esteja otimizado para baixa latência</p>
                 
</p>
 <h3>Testes de Segurança:</h3>
  <p>
<p > 1- Verificar a segurança da hospedagem e do site,incluindo a proteção contra ameaças comuns Web</p>

<p > 2-Assegurar que as melhores práticas de segurança estejam implementadas</p>

</p>
 <h3>Testes de Funcionalidade:</h3>
  <p>
<p > 1-Confirmar que todas as seções e funcionalidades do site estão operacionais</p>
<p > 2-Verificar se os links de contato e outras interações estão funcionando corretamente</p>

</p>
 <h3>Testes de Usabilidade:</h3>
  <p>
  <p > 1-Avaliar a facilidade de navegação e a experiência do usuário no site</p>
<p > 2-Garantir que o design e a estrutura do site sejam intuitivos e eficazes</p>

</p>
 <h3>Procedimento de Monitoramento e Conclusão:</h3>
  <p>

<p > 1-O site será mantido no ar por dois dias para monitoramento</p>

<p > 2-Durante este período, serão realizados os testes acima mencionados</p>

<p > 3-No segundo dia, todos os serviços na AWS serão encerrados</p>


</p>
 <h3>Ferramentas desenvolvimento</h3>
  <p>

<p >🚀 1-HTML</p>

<p >🚀 JavaScript</p>

<p >🚀 3-CSS</p>

<p >🚀 2-Linux</p>

<p >🚀 3-VsCode</p>

<p >🚀 4-Browser</p>

<p >🚀 5-Git/GitHub</p>

</p>
 <h3>Arquitetura do Site na AWS(us-west-1):</h3>
  <p>
 <p>🚀 1-Amazon S3</p>

<p>🚀 2-Bucket Policy: Configurar permissões de acesso ao bucket</p>

<p>🚀 3-Static Website Hosting: Configurar o bucket para hospedar um site estático</p>

<p>🚀 4-Versioning: Habilitar o versionamento para recuperação de dados</p>

<p>🚀 5-CORS: Configurar regras de CORS no S3 se o site acessar recursos de outros domínios.</p>

<p>🚀 6-Redirects e Error Pages: Configurar redirecionamentos e páginas de erro personalizadas no S3.</p>

<p>🚀 7-Amazon CloudFront: Criar e configurar uma distribuição para entregar o conteúdo do S3. Configurar HTTPS para segurança na comunicação. Configurar políticas de cache e comportamento de visualização e Integrar com AWS WAF para proteção adicional.</p>

<p>🚀 8-Performance Tuning: Utilizar o AWS Global Accelerator para melhorar a latência de acesso global.</p>

<p>🚀 9-S3 Lifecycle Policies: Configurar políticas de ciclo de vida para gerenciar o armazenamento e a exclusão automática de objetos.</p>

<p>🚀 10-AWS IAM: Criar e gerenciar políticas de acesso para recursos AWS. Configurar usuários e funções com permissões mínimas necessárias. Configurar users and Roles.</p>

<p>🚀 11-AWS WAF: Configurar Web ACL para proteger o site contra ataques comuns, como SQL injection e XSS. Criar regras específicas para filtrar tráfego malicioso.</p>

<p>🚀 12-AWS Shield: Utilizar o Shield Standard para proteção automática contra ataques DDoS comuns, garantindo que seu site permaneça disponível durante tentativas de ataque.</p>

<p>🚀 13-AWS CloudWatch: Monitorar métricas importantes do S3 e CloudFront. Configurar alarmes para eventos críticos, como aumento de tráfego ou erros. Coletar e analisar logs para detecção de problemas.</p>

<p>🚀 14-AWS Certificate Manager (ACM): SSL/TLS certificates, obter e gerenciar certificados para HTTPS.</p>

<p>🚀 15-AWS Route 53: Domain Registration, registrar novos domínios ou gerenciar domínios existentes. DNS Configuration, configurar registros DNS para apontar para a distribuição CloudFront.</p>

<p>🚀 16-AWS S3 Server Access Logging: Access Logs, habilitar logs para monitorar solicitações feitas ao bucket S3.</p>

<p>🚀 17-Amazon Lambda: Criar funções sem servidor para executar código em resposta a eventos, como uploads no S3 ou chamadas de API. Configurar triggers e permissões para integração com outros serviços AWS, permitindo automação de processos.</p>

<p>🚀 18-Amazon API Gateway: Criar, publicar e gerenciar APIs. Configurar métodos de API para integrar com a Lambda. Habilitar autenticação e controle de acesso, além de monitorar o uso e desempenho da API com CloudWatch.</p>

<p>🚀 19-Git/GitHub</p>

<p>🚀 20-AWS CloudTrail: API Activity Logs, monitorar e registrar chamadas de API feitas para os serviços AWS, ajudando na auditoria e conformidade.</p>

<p>🚀 21-CloudFront Access Logs: Habilitar logs de acesso do CloudFront para análise detalhada.</p>

<h3>Relatórios de testes(incluindo latência, segurança, funcionalidade):</h3>
 <p></p>
 <p></p>
<p></p>
 <p></p>


 <h3>Relatórios de custos com AWS :</h3>
 <p></p>
 <p></p>
 <p></p>
<p></p>
 <p></p>
  <p></p>
 <p></p>
 <p></p>
<p></p>
 <p></p>

<h3>Maior Desafio Superado: </h3>
 <p></p>

 <h3>Maior Apredizado: </h3>
 <p></p>

 <h3>Algum dos requisitos que não foi desenvolvido? Se sim, explique o motivo. </h3>
 <p></p>

 <h3>Pesquisas ou cursos de Referência: </h3>
 <p></p>


<p >
<a href="https://aws.amazon.com/pt/training/restart/">🔗 AWS re/Start-Escola das Nuvens - em andamento </a>
 </p>

<p >
<a href="https://hermes.dio.me/certificates/cover/en/WYXIWZ9T.jpg">🔗 Mentoria 01: Entendendo os aspectos Desenvolvimento Cloud Native</a>
 </p>


<p >
<a href="https://hermes.dio.me/certificates/cover/en/UW35GRLK.jpg">🔗 Introdução a Engenharia de Dados na AWS</a>
 </p>




<p >
<a href="https://hermes.dio.me/certificates/cover/en/D4073BAE.jpg">🔗 Bootcamp GFT Java & AWS Developer</a>
 </p>


<h3>Autora:</h3>

<p>Ana Lúcia N. Lopes de Santana</P>

<h3>Email: </h>
<p>anapedra.mil@gmail.com</P>


<h3>Phone: </h3>
<p>55619993347731</P>


<h3>Lnkedin:</h3>
<p>https://www.linkedin.com/in/anasantana-dev-java-spring/</P>



<h3>Próximo desafio:</h3>

<p>Blog - Um projeto pessoal, monolítico e inspirado no modelo de desenvolvimento cascata.Onde terei um laboratório para implementar e gerenciar um projeto em produção!</p>
<p >
<a href="https://docs.google.com/document/d/1EG9D169szMPGQKsH70VcGKQBkdhZFI-l91a8NXoyaKs/edit">🔗 Visão Geral do negócio e alguns artefatos do projeto 'BLOG'
</a>
 </p>




                     