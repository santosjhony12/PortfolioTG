<img width="1584" height="396" alt="image" src="https://github.com/user-attachments/assets/2424ea5f-2840-42bd-b38c-1f69d1498b99" />

### Em 2023-1

Repositório: <a href="https://github.com/santosjhony12/Sistema_Avaliacao360_1Semestre_BD">Clique aqui</a>

### Empresa Parceira 🫱🏻‍🫲🏻
O projeto foi desenvolvido na Fatec como trabalho acadêmico do primeiro semestre, tendo o professor Lucas Nadalete como cliente interno. O objetivo era criar um sistema de avaliação 360° para ser utilizado em ambientes corporativos ou educacionais, permitindo avaliações multidirecionais (autoavaliação, avaliação por pares, superiores e subordinados).

### Problema ‼️
O processo de avaliações de desempenho da organização é realizado manualmente, gerando dificuldades significativas na gestão e análise dos resultados. Atualmente, as avaliações são registradas em planilhas desconexas, o que dificulta a consolidação dos dados. Além disso, não existe padronização nos critérios utilizados, resultando em inconsistências entre diferentes avaliadores. O processo, além de demorado e burocrático, oferece uma visualização limitada dos resultados, comprometendo a tomada de decisão estratégica e a eficácia na gestão do desempenho dos colaboradores.
### Solução Entregue ✅
Para resolver a problemática, desenvolvemos um sistema desktop completo em Python com as seguintes funcionalidades:
- Interface intuitiva usando TKinter
- Visualização gráfica dos resultados com Matplotlib
- Armazenamento local dos dados em JSON
- Múltiplos perfis de usuário (avaliador/avaliado)
- Geração de relatórios de desempenho
- Sistema básico de autenticação

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
