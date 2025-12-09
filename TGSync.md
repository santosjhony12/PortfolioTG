<img width="1584" height="396" alt="3" src="https://github.com/user-attachments/assets/459ef337-baf7-4d28-b4df-11cb61a94d34" />

### Em 2023-2

Repositório: <a href="https://github.com/TechHorizonBR/API_2_Sem" >Clique aqui</a>

### Empresa Parceira 🫱🏻‍🫲🏻  
O projeto foi desenvolvido na Fatec como trabalho acadêmico do segundo semestre, tendo como cliente o Professor Mineda. Trabalhamos com foco na otimização do processo de avaliação dos Trabalhos de Conclusão de Curso (TCC) dos alunos do 5º e 6º período do curso de Análise e Desenvolvimento de Sistemas.

### Problema ‼️  
O processo de avaliação dos Trabalhos de Conclusão de Curso (TCCs) é realizado de forma manual, o que gera diversas limitações e ineficiências. A execução manual torna o processo suscetível a erros e dificulta a consolidação dos dados de avaliação. Além disso, a geração de relatórios consolidados é trabalhosa e demorada, aumentando o tempo necessário para reunir informações e tomar decisões. A ausência de integração entre entregas, feedbacks e notas compromete a transparência, a agilidade e a padronização do processo avaliativo.

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
- **Comunicação** – Mantive alinhamento constante com o orientador e com os demais colegas, especialmente nos momentos em que houve mudanças de escopo.
- **Trabalho em equipe** – Dividi responsabilidades de forma equilibrada com o grupo, participando das revisões de código para garantir qualidade e aprendizado coletivo.
- **Organização** – Mantive o Trello e o GitHub sempre atualizados, facilitando o acompanhamento do progresso e evitando retrabalho.
- **Adaptabilidade** – Ajustei o sistema para permitir a reimportação de novos CSVs sem apagar os dados existentes, o que exigiu alterações na lógica de importação.
- **Resolução de problemas** – Identifiquei e investiguei um bug crítico que duplicava alunos durante a importação de determinados arquivos. Para solucionar, implementei validações por CPF garantindo a unicidade dos registros.

