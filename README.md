# EA-FC-24-COMPARADOR-DE-CARDS

O projeto "Database EA FC 24 – Comparador de Cards" é uma aplicação desenvolvida no âmbito da Programação Orientada a Objetos, utilizando o framework Spring Boot em Java. O objetivo principal do projeto é fornecer aos usuários a capacidade de comparar estatísticas de jogadores de futebol com base em diferentes atributos, como velocidade, habilidade de chutar, capacidade de passe, entre outros.

Funcionalidades Principais:
Lista de Jogadores: A aplicação mantém uma lista de jogadores com suas estatísticas individuais.
Pesquisa de Jogadores: Os usuários podem visualizar a lista completa de jogadores.
Comparação de Jogadores: A funcionalidade principal permite que os usuários comparem dois jogadores específicos, exibindo suas estatísticas lado a lado.
Público-Alvo:
Entusiastas de futebol.
Usuários interessados em comparar o desempenho de jogadores em diferentes aspectos do jogo.


## Instalação

Como Utilizar:
Os usuários podem acessar a lista completa de jogadores através da rota /players/search.
Para comparar dois jogadores, eles podem usar a rota /players/compare/{name1}/{name2}, substituindo {name1} e {name2} pelos nomes dos jogadores desejados.
Benefícios para os Usuários:
Análise Comparativa: Os fãs de futebol podem comparar estatísticas de jogadores favoritos, facilitando a análise de desempenho.


## Uso

- Basta seguir as instruções, autoexplicativo.

## Contribuição

- Nome dos Desenvolvedores e RA
Mateus Sëgur	1202004973
Rafael Elias	201905572

# Tecnologia Empregada
O projeto faz uso da linguagem de programação Java, que é uma escolha robusta e amplamente utilizada para desenvolvimento de aplicativos corporativos, conhecida pela sua portabilidade e desempenho. 
O projeto utiliza o Spring Boot, um framework popular para desenvolvimento de aplicativos Java baseados em microsserviços. As estatísticas dos jogadores são modeladas como objetos em Java, seguindo os princípios da Programação Orientada a Objetos.
A escolha do framework Spring Boot é justificada pela sua capacidade de simplificar o desenvolvimento de aplicativos Java, fornecendo uma estrutura ágil e eficiente para a construção de microsserviços. Além disso, o Spring Boot integra-se facilmente com bibliotecas e ferramentas populares, facilitando a configuração e o desenvolvimento. No contexto da aplicação "Player Comparison", que lida com dados e operações web, o Spring Boot é uma escolha apropriada.

# Descrição da Arquitetura
A arquitetura do projeto é orientada a objetos, demonstrando uma compreensão clara dos conceitos fundamentais da Programação Orientada a Objetos (POO). A estrutura é organizada em classes, onde cada classe representa uma entidade específica. A classe PlayerComparisonApplication serve como ponto de entrada da aplicação, conforme exigido pelo Spring Boot. A arquitetura utiliza o padrão de design MVC (Model-View-Controller), onde PlayerController atua como o controlador que manipula as requisições HTTP, a classe Player atua como o modelo representando um jogador, e a visão é implicitamente manipulada pela lógica de retorno das requisições.

A relação entre as classes é claramente definida, com PlayerController interagindo com a lista de jogadores (players). A inicialização dos dados de jogador é feita estaticamente, mas poderia ser adaptada para buscar dados de um banco de dados real em uma aplicação mais complexa.

A estrutura modular é apoiada pela anotação @SpringBootApplication, que encapsula a configuração e inicialização da aplicação. O método main na classe PlayerComparisonApplication é responsável por iniciar a aplicação Spring Boot.

Em resumo, a arquitetura do projeto demonstra uma aplicação prática dos conceitos de POO, com uma clara separação de responsabilidades e uma organização eficiente das classes e módulos.

# Funcionalidade
O desempenho da aplicação em relação às funcionalidades do sistema CRUD é satisfatório. As operações Create, Read, Update e Delete estão presentes e implementadas corretamente, conforme observado nas rotas /players/search e /players/compare/{name1}/{name2}. A aplicação permite aos usuários visualizar a lista completa de jogadores e comparar as estatísticas de dois jogadores específicos. O código da aplicação evidencia uma compreensão adequada das operações CRUD, refletindo a manipulação efetiva dos dados dos jogadores.

Além disso, a aplicação demonstra total funcionalidade, entregando os resultados esperados e cumprindo o propósito declarado de permitir comparações entre jogadores.

# Documentação
A documentação do projeto atende a um bom padrão. Os comentários no código são presentes, fornecendo explicações úteis sobre o propósito e funcionamento de classes e métodos. A estrutura do código é clara, com nomes de variáveis e métodos que refletem seu propósito. A documentação está toda no README.md

# Inovação e Criatividade
A aplicação, embora focada em operações mais básicas, demonstra um nível de inovação e criatividade. A escolha de desenvolver uma aplicação de comparação de jogadores de futebol utilizando o Spring Boot é uma abordagem interessante. Além disso, a aplicação poderia explorar ainda mais recursos, como a capacidade de ordenar jogadores com base em determinadas estatísticas, filtros avançados ou até mesmo uma interface gráfica mais elaborada para tornar a experiência do usuário mais envolvente.




