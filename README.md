# Evento 

Propomos um teste unificado para a avaliação de desenvolvedores Frontend/Backend/Full-stack com base em diferentes tópicos que podem ser escolhidos de acordo com os conhecimentos do candidato. 

O objetivo do teste é montar parte(s) de um sistema de loja virtual e entre funcionalidades e tópicos demonstrados. Portanto, não se preocupe em fazer todas as funcionalidades e tópicos listadas abaixo, foque nos que você tem mais conhecimento e facilidade. Sugerimos cerca de 2 funcionalidades a serem feitas para atingir a pontuação.

Sugestões de funcionalidades a serem desenvolvidas e as respectivas pontuações máximas em parênteses:
- Menu de Categorias
- Lista de produtos (vitrine)
- Busca de produtos
- Detalhe de Produto
- Type-ahead (auto-complete) para busca de produtos
- Carrinho de compras
- Cadastro de usuário
- Login
- Página do usuário
- Lista de produtos (administrativo)
- Paginação
- Cadastro de produto

Para desenvolvedores Frontend pode-se mockar os dados no front, mas a demonstração de consumo de APIs é recomendada.

Para desenvolvedores Backend pode-se fazer somente a API em GraphQL ou os endpoints REST c/ Swagger.

Para desenvolvedores Full-stack, é esperado uma aplicação web consumindo um backend em GraphQL ou Rest.

### Entregáveis

Nos envie um email com o(s) link(s) dos repositórios contendo os projetos e opcionalmente um link para a aplicação publicada. Cada repositório deve conter um arquivo README.md como este, explicando brevemente as funcionalidades realizadas, como rodar a aplicação, popular banco de dados etc e opcionalmente quais tópicos abordou. Caso queira publicar seu teste, sugerimos utilizar o **[Heroku](https://heroku.com.br)**, onde é possível criar publicar suas aplicações sem custo e com banco de dados Postgres/MongoDb.

Abaixo seguem os tópicos que gostariamos de ver de acordo com a stack e em parênteses o bônus máximo de pontuação a ser obtido ao atender o tópico. Queremos que nos mostre o seu melhor, então selecione as funcionalidades e tópicos que mais lhe darão oportunidade para mostrar os seus conhecimentos sem a necessidade de tornar o teste extenso.

## Tópicos Comums (Front/Back): 

**Javascript**
- Demonstrar boa legibilidade de código 
- Demonstrar domínio de lógica de programação 
- Demonstrar uso de funcionalidades novas no Javascript (ex: async/wait, spread operators, arrow functions, template literals, etc)
- Demonstrar conhecimento de programação orientada a objetos
- Demonstrar conhecimento de programação funcional 
- Utilização de estruturas imutáveis de dados
- Documentação com JSDocs
- Utilização de scripts npm
- Encadeamento de Promises

**Typescript**
- Demonstrar conhecimento e aplicação de Typescript (interfaces, tipos, união/intersecção de tipos, literais, etc) 
- Utilizar opções de compilação restritas (ex: strict: true)
- Utilizar opção de compilação *strictNullChecks* com uso de tipos null/undefined
- Utilização de type-guards
- Utilização de types auxiliares (ex: Required, Record, etc)
- Utilização de Generics

**Linter**
- Aplicar uso de linter p/ normalizar o estilo do projeto (ex: ESLint, TSLInt)

**Testes**
- Demonstrar conhecimento de testes unitários 
- Demonstrar conhecimento de mock p/ dependências de class
- Atingir bom nível de code-coverage com testes 

**Git**
- Demonstrar boa atomicidade nos commits (ex: único commit por funcionalidade ou bugfix)
- Demonstrar bom uso de mensagens de commit
- Utilizar algum formato padrão de mensagens de commit

**Publicação**
- Publicação de frontend p/ acesso online
- Publicação de backend p/ acesso online 

## Tópicos de Frontend: 
- Criação de aplicação web 
- Uso de requisições HTTP 

**HTML/CSS**
- Layout Visual 
- Demonstrar boa aplicação de layout
- Demonstrar uso de layout responsível
- Demonstrar conhecimento de flex-box
- Demonstrar conhecimento de animações CSS
- Fazer uso de algum padrão de CSS (BEM, SMACSS) 
- Utilizar e fazer uso de recursos de algum framework CSS (ex: SCSS, Stylus, Less, etc)

**UX**: 
- Demonstrar boa navegabilidade
- Utilizar animações/elementos para guiar a experiência do usuário (ex: Indicadores de carregamento, transições de estado/página) 
- Configuração de Progressive-web-app 

**Angular**
- Demonstrar boas práticas de arquitetura 
- Utilizar rotas
- Utilizar módulos
- Utilizar módulos lazy-loaded
- Utilizar serviços
- Configuração e consumo de bibliotecas externas (ex. Angular Material)
- Demonstrar animações utilizando a API do Angular
- Utilizar biblioteca p/ gerenciamento de estado (ex: Apollo Client, NgRx, Akita, Angular-Redux, etc) 
- Tuning de performance de componentes
- Configuração de interceptador de request

**RxJS**
- Demonstrar uso de operadores RxJS (ex. debounce de key strokes, retentativas de request) 
- Demonstrar uso de Subjects (ex: armazenamento de estado) 
- Demonstrar tratamento de erros

**React**
- Demonstrar boas práticas de arquitetura 
- Utilização de functional components
- Utilização de React Hooks
- Utilização de Higher-Order-Components
- Utilização de pattern de container/presentational components
- Utilização de algum gerenciador de estado (Apollo Client, Redux, MobX, etc) 
- Integração com outras bibliotecas
- Lazy-load de componentes
- Utilização com Typescript 

## Tópicos de Backend:

**NodeJS** 
- Criação de aplicação NodeJS 
- Uso de banco de dados relacional/não relacional 
- Script p/ estrutura do banco 
- Script p/ popular banco 
- Utilização de middlewares
- Utilização de JSON Web Tokens p/ autenticação 
- Validação de dados das requests
- Utilizar alguma ferramenta p/ auxilar o desenvolvimento (nodemon, node-dev, ts-node-dev, etc)

**GraphQL**
- Criação de endpoint GraphQL 
- Construir operações de Query
- Construir operações de Mutation
- Construir operações de Subscription
- Utilizar alguma união de tipo

**REST**
- Criação de endpoints REST p/ consumo do front
- Documentar a API com uso de Swagger 

**Docker**
- Configurar docker p/ as aplicações 


### Ferramentas

Imagens de placeholder - http://lorempixel.com/

Mock de APIs 
- https://reqres.in/
- https://www.mocky.io/
- https://jsonplaceholder.typicode.com/
