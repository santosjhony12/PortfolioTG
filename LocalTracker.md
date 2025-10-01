<img width="1584" height="396" alt="5" src="https://github.com/user-attachments/assets/1e6a1d36-b0c2-4ad9-a607-227d59506fc5" />

### Em 2024-2

Repositório: <a href="https://github.com/TechHorizonBR/API_4SEM">Clique aqui</a>

#### Empresa Parceira 🫱🏻‍🫲🏻
O projeto foi realizado em parceria com a ITO1, uma empresa especializada em dados e IoT. A ITO1 coleta informações de diferentes ambientes usando dispositivos IoT e utiliza essas informações para inovar nas soluções, especialmente na geolocalização de pessoas e objetos. O foco é gerenciar grandes volumes de dados gerados por IoTs de maneira eficiente, oferecendo soluções escaláveis e de alta disponibilidade para registrar e consultar geolocalização de dispositivos, ativos e outros objetos em banco de dados relacional.

#### Problema ‼️
O grande volume de dados gerados por dispositivos IoT, especialmente relacionados à geolocalização, apresenta desafios significativos de armazenamento, escalabilidade e desempenho. A necessidade de consultas rápidas e de garantir alta disponibilidade para múltiplos usuários e dispositivos torna o processo ainda mais complexo. Além disso, é fundamental assegurar a integridade e a rastreabilidade das informações, evitando perdas ou inconsistências que possam comprometer a confiabilidade da solução.
#### Solução Entregue ✅
A solução desenvolvida foi um sistema que integra o registro e consulta de dados de geolocalização de dispositivos, com funcionalidades para visualização em mapa, filtros de busca, e demarcação de espaços para alertas. O sistema foi projetado para ser escalável, intuitivo e com alta disponibilidade, utilizando tecnologias de ponta e um banco de dados relacional. Entre as funcionalidades entregues estão:
- Registro de dados do cliente;
- Visualização do dispositivo em tempo real no mapa;
- Filtros de busca e intervalos de datas para consultas;
- Criação de alertas quando dispositivos saem de áreas demarcadas;
- Rastreabilidade do histórico de localizações;
- Gestão de usuários e autenticação de acesso.



#### Tecnologias Utilizadas
- Java 17: Versão estável da linguagem Java, com melhorias de desempenho, novas funcionalidades, e suporte de longo prazo (LTS).
- Spring Boot: Framework Java que simplifica o desenvolvimento de aplicações, oferecendo configurações automáticas e ferramentas para criar serviços e APIs.
- Spring Security: Módulo do Spring para a segurança de aplicações, incluindo autenticação e autorização.
- Hibernate: Framework ORM para interação entre aplicações Java e bancos de dados relacionais.
- HTML (HyperText Markup Language): Linguagem de marcação para criar a estrutura e conteúdo de páginas da web.
- CSS (Cascading Style Sheets): Linguagem de estilo para estilizar páginas web.
- JavaScript: Linguagem de programação para interatividade em sites e aplicações web.
- Oracle: Sistema de gerenciamento de banco de dados relacional para armazenamento e consulta de dados.
- Pinia: Para gerenciamento de estado no front-end com Vue.js.
- Vue.js: Framework JavaScript para construção de interfaces de usuário interativas.
- Figma: Ferramenta para prototipagem de interfaces e design de soluções.



#### Contribuições Pessoais
- Durante o projeto, desempenhei o papel de **Scrum Master** e contribui de maneira significativa no desenvolvimento tanto do **back-end** quanto do **front-end**. Fui responsável pela criação de endpoints de rastreabilidade de usuário, processamento de dados, e pela integração das funcionalidades de geolocalização no sistema. As contribuições específicas incluem:

  - Registro de Dados e Rastreabilidade de Usuário
          <details>
              Desenvolvi o sistema de rastreabilidade de usuários, garantindo que cada ação fosse registrada. Enfrentei dificuldades iniciais ao capturar corretamente o usuário logado, mas após ajustes no Spring Security, implementei uma solução funcional, assegurando que todos os endpoints exigissem um usuário autenticado.
      ![image](https://github.com/user-attachments/assets/21a21d3d-2b52-44db-b21c-0038292be875)
          </details>

  - Processamento e Leitura de Arquivos CSV
          <details>
              Desenvolvi um algoritmo que processava arquivos CSV enviados por HTTP (POST), transformando-os em dados utilizáveis para o banco de dados relacional. A solução foi usada tanto para configuração de bases de dados quanto para o upload de dados com esquema pronto.
      ![image](https://github.com/user-attachments/assets/b2404759-428c-4847-a790-29173be97b49)
          </details>

  - Gerenciamento de Usuários
          <details>
              Desenvolvi a funcionalidade de gerenciamento de usuários, permitindo o registro e a manutenção dos dados dos usuários no sistema. A solução inclui operações para criação, atualização e exclusão de usuários, bem como a validação de dados de entrada (como e-mail e senha). A interface de gerenciamento foi construída utilizando **Spring Boot**, integrando com o banco de dados relacional para armazenamento das informações de usuários, como nome, e-mail, senha criptografada e status de ativação. A implementação inclui a criação de um **usuário administrador** com permissões para gerenciar todos os outros usuários do sistema, podendo alterar dados e até excluir contas de usuários quando necessário.
      ![image](https://github.com/user-attachments/assets/80b9ea1a-6b2c-401a-8617-e84a22540ce5)
          </details>

  - Autenticação de Usuários
          <details>
              Implementei o processo de autenticação de usuários utilizando **Spring Security** com autenticação baseada em **JWT (JSON Web Tokens)**. Esse sistema permite que os usuários façam login utilizando e-mail e senha, gerando um token JWT que é usado para validar requisições subsequentes. O processo de login envolve a verificação da senha criptografada com **BCrypt** para garantir a segurança das informações. Após a autenticação bem-sucedida, o sistema gera um token JWT que pode ser utilizado em futuras requisições para acessar endpoints protegidos. Além disso, foi configurado um sistema de **roles**, onde os usuários podem ser atribuídos a diferentes níveis de acesso (ex: administrador, usuário comum), permitindo controle granular sobre o que cada usuário pode acessar no sistema.
      ![image](https://github.com/user-attachments/assets/75b554db-84c2-4eb5-a282-4981a0d6f057)
          </details>


### Hard Skills

- Java (Spring Boot): A implementação do **gerenciamento de usuários** e da **autenticação de usuários** demonstra meu domínio em desenvolvimento de back-end, especialmente no uso do Spring Boot. O uso de **Spring Security** e JWT para autenticação, além de integrar com banco de dados relacional, mostra uma boa aplicação de conceitos avançados de segurança e arquitetura de sistemas.
- Oracle: No desenvolvimento do **gerenciamento de usuários**, trabalhei com banco de dados relacional, modelando e realizando consultas para armazenar e gerenciar informações de usuários, como nome, e-mail e senha criptografada.
- Vue.js e Pinia: Embora o foco principal das minhas contribuições tenha sido o back-end, o uso de Vue.js e Pinia no front-end seria crucial para criar interfaces interativas e integrar essas funcionalidades de back-end com a experiência do usuário.
- Git/GitHub: O versionamento de código e a colaboração em equipe, tanto para a implementação do **processamento de arquivos CSV** quanto para o **gerenciamento de usuários**, requerem uma boa organização de repositórios e controle de versões.
- Postman: Ao desenvolver as funcionalidades de rastreabilidade de usuários e autenticação, utilizei ferramentas como o Postman para testar e validar as APIs, garantindo que os endpoints estivessem funcionando corretamente.
- Jira: No gerenciamento das tarefas relacionadas a essas funcionalidades, utilizei o Jira para organizar as atividades, acompanhar o progresso do projeto e garantir a entrega dentro do prazo.

### Soft Skills

- Comunicação: Em todas as minhas contribuições, especialmente como parte da **dev team**, facilitei a comunicação dentro da equipe. Isso foi vital, por exemplo, na resolução das dificuldades ao capturar corretamente o usuário logado no **sistema de rastreabilidade de usuários** e no ajuste da implementação de autenticação no **Spring Security**.
- Trabalho em Equipe: Durante o desenvolvimento do **gerenciamento de usuários** e da **autenticação de usuários**, colaborei ativamente com outros membros da equipe para garantir que o sistema estivesse funcionando de forma coesa, implementando soluções técnicas de forma eficaz e dentro dos requisitos do projeto.
- Organização: A organização foi um ponto chave para entregar as funcionalidades de forma eficiente, especialmente ao lidar com o processamento de arquivos CSV, o que exigia um bom gerenciamento de tempo entre as responsabilidades acadêmicas e profissionais.
- Adaptabilidade: A solução que implementei para a **rastreabilidade de usuários** exigiu ajustes no **Spring Security** e uma adaptação aos feedbacks recebidos durante o desenvolvimento, o que demonstra minha capacidade de ajustar as abordagens conforme as necessidades do projeto.
- Resolução de Problemas: Enfrentei diversos desafios técnicos, como a captura correta do usuário logado e a implementação de **segurança na autenticação**. A solução eficiente para esses problemas garantiu o funcionamento adequado das funcionalidades, como a validação de autenticação e o gerenciamento de permissões com **JWT**.
