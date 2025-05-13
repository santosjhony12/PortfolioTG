# Jhony Santos de Souza

## Introdução

Me chamo Jhony. Tenho 20 anos. Sou um desenvolvedor de software com uma paixão por criar soluções inovadoras e eficientes de software. Estou cursando tecnólogo em Banco de Dados na Fatec São José dos Campos, com formação técnica em Desenvolvimento de Sistemas pela Etec. Atualmente, sou Analista de Dados Junior em uma multinacional líder na indústria do vidro, onde também atuei como estagiário e aprendiz. Tenho familiaridade com metodologias ágeis como Scrum, que aplico em projetos para trabalhar em equipe e alcançar bons resultados.

## Contatos
* [GIT](https://www.github.com/santosjhony12)
* [LinkedIn](www.linkedin.com/in/jhonysouzadev)

## Meus Principais Conhecimentos
Tenho conhecimento sólido em desenvolvimento web, utilizando frameworks como Django e Spring Boot para criação de aplicações robustas. No front-end, uso Vue.js com TypeScript, priorizando uma abordagem eficiente e reativa. Minha experiência com bancos de dados inclui MySQL, Postegress, SQLServer e Oracle para dados relacionais e MongoDB para dados NoSQL, aplicados de forma integrada em projetos como no uso do Oracle Cloud.

Possuo conhecimento em automação e manipulação de dados com Power Query, Excel, PowerBI e PowerApps onde integro fontes de dados de sistemas como SAP para gerar relatórios e KPIs para controle de produção.

Adoto metodologias ágeis, especialmente Scrum, para gerenciamento de projetos, e já desenvolvi soluções de visualização de dados usando Power BI. Tenho experiência na visualização de mapas utilizando MapTiler, aplicados em projetos Vue.js, o que me permite lidar com projetos que envolvem tanto o back-end quanto o front-end de forma eficaz.

## Meus Projetos

### Em 2023-1

### Empresa Parceira 🫱🏻‍🫲🏻
O projeto foi desenvolvido na Fatec como trabalho acadêmico do primeiro semestre, tendo o professor Lucas Nadalete como cliente interno. O objetivo era criar um sistema de avaliação 360° para ser utilizado em ambientes corporativos ou educacionais, permitindo avaliações multidirecionais (autoavaliação, avaliação por pares, superiores e subordinados).

### Problema ‼️
O principal desafio era substituir o processo manual de avaliações de desempenho, que apresentava os seguintes problemas:

- Dificuldade na consolidação das avaliações (planilhas desconexas)
- Falta de padronização nos critérios de avaliação
- Processo demorado e burocrático
- Visualização limitada dos resultados

### Solução Entregue ✅
Para resolver a problemática, desenvolvemos um sistema desktop completo em Python com as seguintes funcionalidades:
- Interface intuitiva usando TKinter
- Visualização gráfica dos resultados com Matplotlib
- Armazenamento local dos dados em JSON
- Múltiplos perfis de usuário (avaliador/avaliado)
- Geração de relatórios de desempenho
- Sistema básico de autenticação

Repositório: <a href="https://github.com/santosjhony12/Sistema_Avaliacao360_1Semestre_BD">Clique aqui</a>

#### Tecnologias Utilizadas
- Python: Linguagem de programação interpretada e de alto nível, utilizada como base principal do projeto por sua simplicidade, legibilidade e ampla gama de bibliotecas que facilitam o desenvolvimento de aplicações robustas.
- Tkinter: Biblioteca padrão do Python para criação de interfaces gráficas (GUI), permitindo o desenvolvimento de janelas, botões, menus e outros elementos visuais de forma nativa e integrada à linguagem.
- Matplotlib: Biblioteca de visualização de dados em Python que permite a criação de gráficos estáticos, animados e interativos, sendo amplamente utilizada para análise e apresentação de informações visuais.
- JSON (JavaScript Object Notation): Formato leve de intercâmbio de dados, utilizado no projeto para armazenamento local de informações de forma estruturada e de fácil leitura tanto para humanos quanto para máquinas.
- Git/GitHub: Ferramentas de controle de versão e colaboração. O Git permite rastrear alterações no código-fonte, enquanto o GitHub oferece uma plataforma online para hospedar repositórios, facilitar o trabalho em equipe e gerenciar o desenvolvimento do projeto.
- Notion: Aplicativo multifuncional de produtividade utilizado para o gerenciamento do projeto, organização de tarefas, documentação e acompanhamento do progresso da equipe de forma centralizada e colaborativa.
- Discord: Plataforma de comunicação por texto, voz e vídeo, utilizada pela equipe para reuniões, troca de ideias e alinhamento em tempo real, promovendo colaboração contínua durante o desenvolvimento do projeto.

Contribuições Pessoais
- Durante o projeto atuei como dev-team, trabalhando na interface de usuário e com funcionalidades da avaliação 360º:

    - Interface de Usuário
          <details>
              Com o primeiro contato com o desenvolvimento desktop, desenvolvi telas/interfaces intuitivas para o usuário, buscando facilidade e usabilidade por meio da biblioteca CustomTkinter, do Python. Inicialmente, tentei desenvolver com a biblioteca padrão (Tkinter), mas, após algumas pesquisas, encontrei uma opção mais moderna e personalizável. Vale ressaltar que se trata de uma biblioteca simples e fácil de utilizar; contudo, enfrentei sérios problemas relacionados à responsividade já que o mesmo utiliza pixel.
          ![image](https://github.com/user-attachments/assets/e0f7e4fc-fbab-4fa5-8c3c-d704e2213b6f)
          </details>

    - Desenvolvimento de cálculos e feedbacks ao usuário na avaliação
          <details>
              Desenvolvi calculos para a avaliação. Gerando pontuações com base na avaliação interpessoal e pessoal. Utilizando calculos simples e registrando as respostas em nosso banco de dados Json. Essa etapa foi importante para garantir a integridade dos cálculos e pelo resultado da avaliação do integrante. Qualquer erro poderia causar incoerência no feedback ao usuário.
          ![image](https://github.com/user-attachments/assets/7351eccd-5e05-4032-9ac8-2e8d88af7de7)
          </details>

    - Desenvolvimento dos painés de gerenciamento de usuário
          <details>
              Para o cadastro de usuário, utilizamos um método de requisição de entrada, onde somente se o administrador do sistema aprovar a entrada, o usuário consegue acessar o sistema. Além disso, o próprio usuário solicita em qual grupo ele deseja participar.
          ![image](https://github.com/user-attachments/assets/78dc2087-c4a1-4ee7-88b4-ad09500d0010)
          </details>

    - Desenvolvimento dos painés de gerenciamento de usuário
          <details>
              Auxiliei no desenvolvimento da lógica de criação dos períodos avaliativos, onde somente o administrador do sistema possui acesso. Importante dizer, que nessa etapa, operei somente com a lógica do programa, dando espaço para o visual para outro integrante do grupo.
          ![image](https://github.com/user-attachments/assets/8d9a7c4e-a261-4d12-9664-50063ab75b95)
          </details>

    - Desenvolvimento do sistema de autenticação
          <details>
              Auxiliei no desenvolvimento da lógica da autenticação de usuário. Nesse projeto, não utilizamos hash para criptografia para garantir a segurança do sistema. A recuperação de senha foi feita através de ```for``` buscando pelo email do usuário.
          ![image](https://github.com/user-attachments/assets/0df9ff0a-2987-4c92-b08f-568434a35172)
          </details>


#### Hard Skills
- Python - Desenvolvi a aplicação desktop, configurando toda lógica e visual com a linguagem de programação, como também em conexão ao banco de dados.
- Json - Utilizei como banco de dados, simulando um não relacional.
- VS Code - Ferramenta utilizada no desenvolvimento do projeto, com alto nível de proficiência na customização do ambiente e uso de plugins.
- Git/GitHub - Versionamento de código e trabalho em equipe, com eficiência no uso de branches, pull requests e resolução de conflitos.
- Figma - Para prototipagem de interfaces e colaboração no design da solução, utilizando a ferramenta com eficiência.
- Notion - Organizei tarefas e acompanhei o desenvolvimento do projeto de acordo com a metodologia Scrum.
- Discord - Utilizei para comunicação com o tipo, além de reuniões onlines.

#### Soft Skills
- Comunicação – Mantive um diálogo constante com os colegas para esclarecer dúvidas técnicas, alinhar decisões de implementação e garantir a integração fluida entre as partes do sistema. Essa comunicação foi essencial principalmente na fase de testes e ajustes finais.
- Trabalho em equipe – Colaborei diretamente com os demais desenvolvedores nas funcionalidades de autenticação, avaliação e gestão de usuários. Compartilhei ideias, dividi responsabilidades e solicitei apoio quando necessário, contribuindo para um desenvolvimento colaborativo.
- Organização – Utilizei ferramentas como Notion e GitHub para gerenciar minhas tarefas e commits, mantendo o andamento do projeto em dia mesmo com as exigências das disciplinas acadêmicas paralelas.
- Adaptabilidade – Durante as sprints, precisei ajustar o código de cálculo das avaliações após mudanças nos critérios definidos pelo cliente interno. Reestruturei a lógica rapidamente, garantindo que o sistema atendesse aos novos requisitos sem comprometer a estabilidade.
- Resolução de problemas – Enfrentei dificuldades técnicas ao implementar o armazenamento e leitura de dados em JSON, especialmente na etapa de cálculo de pontuação. Analisei os erros, testei alternativas e otimizei o processo para evitar inconsistências nos resultados das avaliações.


### Em 2023-2

### Empresa Parceira 🫱🏻‍🫲🏻  
O projeto foi desenvolvido na Fatec como trabalho acadêmico do primeiro semestre, tendo como cliente o Professor Mineda. Trabalhamos com foco na otimização do processo de avaliação dos Trabalhos de Conclusão de Curso (TCC) dos alunos do 5º e 6º período do curso de Análise e Desenvolvimento de Sistemas.

### Problema ‼️  
O principal desafio era modernizar e automatizar o processo de avaliação dos TCCs, que até então apresentava diversas limitações:

- Processos manuais e suscetíveis a erros
- Consolidação ineficiente de dados de avaliação
- Dificuldade na geração de relatórios consolidados
- Tempo excessivo para reunir informações e tomar decisões
- Falta de integração entre entregas, feedbacks e notas

### Solução Entregue ✅  
Para resolver essa problemática, desenvolvemos uma aplicação desktop robusta com os seguintes recursos:

- Upload de arquivos CSV com dados de alunos
- Validação automática dos dados do orientador
- Registro de notas e feedbacks por parte dos professores
- Cadastro e acompanhamento de entregas
- Geração automatizada de relatórios diversos:
  - Alunos aptos à defesa
  - Relatório de notas
  - Acompanhamento de entregas
  - Certificados de orientação

#### Tecnologias Utilizadas  
- **Java**: Linguagem de programação principal usada no backend da aplicação, oferecendo segurança e escalabilidade.
- **JavaFX**: Utilizada para o desenvolvimento da interface gráfica do sistema desktop.
- **MySQL**: Banco de dados relacional utilizado para armazenar os dados dos alunos, orientadores e avaliações.
- **IntelliJ**: IDE utilizada para o desenvolvimento da aplicação com foco em produtividade e integração.
- **Git/GitHub**: Ferramentas para versionamento de código e colaboração em equipe.
- **Figma**: Utilizado na prototipação e design das interfaces da aplicação.
- **draw.io**: Ferramenta de diagramação utilizada na modelagem dos processos e entidades.
- **BRmodelo**: Utilizado para modelagem do banco de dados relacional.
- **Trello**: Para o gerenciamento ágil do projeto e acompanhamento das tarefas.
- **Discord**: Comunicação contínua entre a equipe para alinhamento e reuniões online.

### Contribuições Pessoais  
- Durante o projeto, atuei diretamente no desenvolvimento da aplicação e participei das seguintes tarefas:

    - Interface de Usuário (JavaFX)
          <details>
              Trabalhei na criação de telas intuitivas para facilitar a usabilidade dos professores e coordenadores. Focando em simplificar o processo de upload de arquivos CSV, visualização dos dados e fornecimento de feedbacks, utilizei JavaFX para criar interfaces claras e de fácil navegação. Também implementei validações visuais para garantir que os dados fossem inseridos corretamente.
          ![image](https://github.com/user-attachments/assets/47731d51-6f8e-43a0-b0dc-25ab28c0697c)
          </details>

    - Validação e Cadastro de Dados
          <details>
              Implementei a lógica de leitura e validação dos arquivos CSV, assegurando que os dados fossem corretamente importados para o banco de dados, mantendo sua integridade e consistência durante o processo.
          ![image](https://github.com/user-attachments/assets/78b2e33c-c2aa-4af4-94ae-e3f58b0d2fbd)
          </details>

    - Funcionalidade de Feedbacks
          <details>
              Desenvolvi o módulo de inserção de notas e comentários dos orientadores, permitindo que eles registrassem avaliações detalhadas sobre o desempenho dos alunos. Esse módulo não só facilitou a documentação do progresso acadêmico, mas também proporcionou um espaço para feedback construtivo, contribuindo para uma avaliação mais completa e personalizada de cada aluno.
          ![image](https://github.com/user-attachments/assets/1e7effcc-42e4-46c7-be4d-50fb9ea94d10)
          </details>

    - Visualização de Orientadores
          <details>
              Desenvolvi a conexão com o banco de dados utilizando JDBC e implementei a visualização dos orientadores cadastrados em uma tabela no JavaFX. Isso permitiu uma interação eficiente com os dados armazenados, proporcionando uma exibição clara e dinâmica das informações dos orientadores diretamente na interface do usuário.
          ![image](https://github.com/user-attachments/assets/d65dea43-ba29-41e5-8339-b3bbcf306dce)
          </details>

    - Geração de Relatórios
          <details>
              Auxiliei na criação dos relatórios que possibilitam o acompanhamento das entregas dos alunos, a avaliação da aptidão para defesa e a emissão de certificados. Esses relatórios foram projetados para fornecer informações claras e objetivas, facilitando o monitoramento do progresso dos alunos e a gestão das atividades acadêmicas.
          ![image](https://github.com/user-attachments/assets/33fd096e-2c74-4a7c-a510-f3658614435a)
          </details>
  
### Hard Skills  
- **Java** – Desenvolvi funcionalidades para importar e processar os dados dos alunos a partir de arquivos CSV. Tivemos dificuldades em tratar formatações incorretas no CSV, o que exigiu validações robustas e tratamento de exceções.
- **JavaFX** – Construí telas para visualização dos alunos, avaliação e emissão de relatórios. O desafio foi organizar a interface para facilitar o uso pelos professores, que não necessariamente têm familiaridade com sistemas.
- **MySQL** – Modelei o banco relacional para armazenar alunos, avaliações, feedbacks e relatórios. Durante o projeto, refatoramos tabelas para incluir novos dados exigidos após mudanças nos requisitos.
- **Git/GitHub** – Gerenciamos o versionamento com branches específicas por funcionalidade. Tivemos conflitos de merge quando dois membros alteraram a mesma classe, o que nos levou a melhorar a comunicação e revisar PRs com mais atenção.
- **Figma** – Interpretamos protótipos simples para organizar o fluxo de telas e campos. Ajustes foram necessários conforme surgiam novas necessidades do professor e da coordenação.
- **draw.io** – Criamos diagramas de fluxo e entidade-relacionamento para mapear os processos desde a leitura do CSV até a geração dos relatórios.
- **BRModelo** – Utilizamos para modelar inicialmente o banco. Precisamos alterar a modelagem após percebermos que feedbacks e avaliações deveriam ser entidades distintas.
- **IntelliJ** – Usamos como IDE principal, com foco em produtividade, integração com Git e execução dos testes.
- **Trello** – Acompanhamos as tarefas por sprints. Em algumas ocasiões, acumulamos demandas não previstas, o que exigiu reorganização do backlog.
- **Discord** – Foi nosso principal canal de comunicação diária para tirar dúvidas rápidas e tomar decisões técnicas em conjunto.

### Soft Skills  
- **Comunicação** – Mantivemos alinhamento constante com o orientador e entre os membros do grupo, especialmente em momentos de mudança de escopo.
- **Trabalho em equipe** – Dividimos responsabilidades de forma equilibrada, com revisões de código entre colegas para garantir a qualidade e aprendizado coletivo.
- **Organização** – Mantivemos o Trello e GitHub atualizados, o que facilitou acompanhar o progresso e evitar retrabalho.
- **Adaptabilidade** – Precisamos adaptar o sistema para permitir reimportação de novos CSVs sem apagar os dados existentes, o que implicou mudanças na lógica de importação.
- **Resolução de problemas** – Um bug crítico causava duplicação de alunos ao importar certos arquivos. Investigamos o problema e adicionamos validações por CPF para garantir unicidade.


### Em 2024-1

#### Empresa Parceira 🫱🏻‍🫲🏻
O projeto foi realizado em parceria com a Dom Rock, uma empresa que possui uma arquitetura de processamento de dados em pipeline, utilizada para orquestrar dados e algoritmos de inteligência artificial, ou modelos matemáticos, de acordo com as necessidades de negócio de seus clientes. Essa plataforma é amplamente aplicada em diferentes indústrias para tratar grandes volumes de dados, gerando insights automatizados e facilitando a tomada de decisão.

#### Problema ‼️
O principal desafio enfrentado era o processo manual de configuração das fontes de dados. Esse processo, fundamental para a operação da plataforma, exigia muito tempo e envolvimento de técnicos especializados. A configuração manual não apenas limitava a agilidade na implantação da solução para os clientes, como também tornava a operação dependente de profissionais altamente qualificados para garantir que os dados estivessem corretamente preparados para os estágios subsequentes do pipeline.

#### Solução Entregue ✅
Para resolver esse problema, a equipe desenvolveu uma interface amigável e intuitiva que permitia a configuração das fontes de dados de forma automatizada. A solução envolveu o desenvolvimento de várias interfaces, incluindo uma para o cadastro de clientes, soluções e usuários, e outra para upload de arquivos CSV ou Excel com a visualização da estrutura de dados. Também foi criado um dashboard para administradores com visões quantitativas sobre os dados configurados. Além disso, a solução incluiu funcionalidades de mapeamento de campos-chave e aplicação de regras de negócios, além de um sistema de autenticação e auditoria para rastreabilidade. Isso trouxe benefícios como maior agilidade nas implantações e redução da dependência de técnicos especialistas

Repositório: <a href="https://github.com/TechHorizonBR/API_3SEM.git">Clique aqui</a>

#### Tecnologias Utilizadas
- Java 17: Uma versão estável da linguagem de programação Java, com melhorias de desempenho, novas funcionalidades, e suporte de longo prazo (LTS).
- Spring Boot: Framework Java que simplifica o desenvolvimento de aplicações, oferecendo configurações automáticas e ferramentas prontas para criar serviços e APIs.
- Spring Security: Módulo do Spring voltado para a segurança de aplicações, incluindo autenticação e autorização.
- Hibernate: Framework de mapeamento objeto-relacional (ORM) que facilita a interação entre aplicações Java e bancos de dados relacionais.
- HTML (HyperText Markup Language): Linguagem de marcação usada para criar a estrutura e o conteúdo básico de páginas da web.
- CSS (Cascading Style Sheets): Linguagem de estilo utilizada para estilizar páginas da web, definindo cores, layouts e fontes.
- JavaScript: Linguagem de programação usada para criar interatividade e dinamicidade em sites e aplicações web.
- MySQL: Sistema de gerenciamento de banco de dados relacional amplamente utilizado para armazenar e consultar dados de forma estruturada.
- Discord: Plataforma de comunicação em tempo real que permite enviar mensagens, realizar chamadas de voz e vídeo, além de criar comunidades organizadas por servidores.
- Jira: Ferramenta de gerenciamento de projetos e acompanhamento de tarefas, frequentemente usada em equipes que seguem metodologias ágeis como Scrum ou Kanban.
- BRModelo: Ferramenta gráfica para criação e modelagem de diagramas de banco de dados, como modelos entidade-relacionamento (ER).

#### Contribuições Pessoais
- Durante o projeto desenvolvi como back-end, front-end  e Scrum master. Fui responsável por criação de endpoints de rastreabilidade de usuário dentro do sistema, processamento e leitura de arquivos CSV, padronização de estilos no front-end, estruturação dos modelos conceituais e lógicos de banco de dados e acompanhamento de desenvolvimento da equipe de programação. 

    - Rastreabilidade de usuário
          <details>
              Identificar o usuário logado no sistema e registrar todas as ações executadas. A principio, enfrentei dificuldades para capturar o usuário através do Spring Security, o que exigiu esforços para o desenvolvimento do histórico. Depois de testes e refatorações, cheguei a uma solução vigente de registrar a ação toda vez que fosse chamado um endpoint, exigindo obrigatoriamente que o usuário esteja logado para realizar qualquer tipo de requisição HTTP (exceto requisições de login).
          ![image](https://github.com/user-attachments/assets/487c705d-a150-4a03-a39f-003f74672166)
          </details>
    - Processamento e leitura de arquivos CSV
          <details>
              Desenvolvi um algoritmo capaz de capturar um arquivo CSV através de uma requisição HTTP(POST) convertido em código binário, logo transformar novamente em arquivo e ler através de um Buffered, em seguida, fiz o processamento do CSV utilizando bibliotecas importadas do Java e realizei o input dos dados para o banco de dados relacional. Importante ressaltar, foi utilizado o método duas vezes em dentro do sistema, sendo a primeira para configuração de uma base de dados, e a segunda para upload de dados com a configuração do esquema pronto.
      ![image](https://github.com/user-attachments/assets/239ff7f4-0254-4f62-b084-a4bf35ef017a)
          </details>
    - Padronização de estilos no Front-end
          <details>
              Ao final do projeto, auxiliei os desenvolvedores fron-ends na padronização dos estilos das interfaces do sistema. Enfretei algumas dificuldades, já que não utilizamos nenhum framework de estilização, precisei replicar muito trecho de código em diversas telas, gerando um retrabalho do que já estava feito. Todavia, com refatorações e ajustes, consegui centralizar em arquivos CSS padrões para consumir em mais de uma tela, diminuindo o excesso de código duplicado no sistema.
      ![WhatsApp Image 2024-08-19 at 20 02 03](https://github.com/user-attachments/assets/2efd4a6d-8962-459b-a8f6-02c68a5731f2)
          </details>
          
    - Modelos de Banco de Dados Conceituais e Lógicos
        <details>
              Contribui para o desenvolvimento dos modelos Conceituais e Lógicos de banco de dados. No primeiro momento, tive dificuldades para o modelo inicial, já que não possuia um entendimento completo e concreto do projeto. Todavia, com o progresso das Sprints foi possível ter uma visão mais ampla da aplicação facilitando o desenvolvimento do DER e entendimento dos relacionamentos entre as entidades de banco de dados. 
      

      ![LOGICO_API_DOM_ROCK_V3_PNG](https://github.com/user-attachments/assets/5d28e1ce-ae8c-4c02-9a9c-2b96dc94c55f)
        </details>
 
        
  - Acompanhamento do desenvolvimento da equipe Scrum
          <details>
              Nesse projeto, tive a oportunidade de trabalhar com a equipe como Scrum Master, ficando com atividades de gerenciamento de tasks e da equipe Scrum. Durante o processo, observei dificuldades nos desenvolvedores em quesitos técnicos, dessa forma, obtive a estratégia de rever as tasks e redistribui-las, contudo, auxiliando e reforçando o estudo das tecnologias.
      ![image](https://github.com/user-attachments/assets/3259426c-c849-4a10-8e64-0e115e1e1ca9)
          </details>


#### Hard Skills
- Java (Spring Boot) - Desenvolvi aplicações backend, configurando endpoints e integrações de forma autônoma.
- MySQL - Utilizei para modelagem e gerenciamento de dados relacionais, com capacidade plena de criação de queries e ajustes no banco de dados.
- IntelliJ IDEA - Ferramenta utilizada no desenvolvimento do projeto, com alto nível de proficiência na customização do ambiente e uso de plugins.
- Git/GitHub - Versionamento de código e trabalho em equipe, com eficiência no uso de branches, pull requests e resolução de conflitos.
- Postman - Testei e validei APIs durante o desenvolvimento, com conhecimento para criação de coleções de testes.
- Figma - Para prototipagem de interfaces e colaboração no design da solução, utilizando a ferramenta com eficiência.
- BR Modelo - Utilizado para modelagem de dados, com proficiência no uso de diagramas ER.
- Jira - Organizei tarefas e acompanhei o desenvolvimento do projeto de acordo com a metodologia Scrum.
- HTML5, CSS3, JavaScript - Usei no desenvolvimento frontend, criando interfaces responsivas e dinâmicas, com autonomia.

#### Soft Skills
- Comunicação - Foi essencial para alinhar as expectativas da equipe durante as reuniões de planejamento e revisões de sprint. Utilizei principalmente sendo Scrum Master, quando alguns membros da equipe deixavam de realizar as tasks dentro do prazo.
- Trabalho em equipe - Utilizei para desenvolver em conjunto o back-end, principalmente no momento da criação de rastreabilidade de usuário no sistema, solicitando ajuda aos demais.
- Organização - Mediante prazos de entrega das Sprints e as disciplinas, precisei me organizar para cumprir conforme planejado, principalmente em períodos de provas.
- Adaptabilidade - Houve a necessidade de ajustar a implementação das funcionalidades conforme feedbacks dos clientes e mudanças nos requisitos durante o processo de desenvolvimento, por exemplo, adicionar mais uma leitura de arquivo no final da Sprint 4.
- Resolução de problemas - Enfrentei desafios técnicos na integração de dados, por exemplo, na leitura do arquivo CSV (Sprint 1), e precisei aplicar soluções criativas e eficientes para garantir a continuidade do projeto sem impactar os prazos.

