# Mercado Livre

Aplicação para teste da vaga Front-End no Mercado Livre.

## GIT

### Subtrees
O repositório principal é composto por duas subtrees, contribuindo com a manutenibilidade das camadas client e server. Essa abordagem permite que cada subtree possua seu repositório com suas próprias injeções de dependências, podendo ser integrado com outros sistemas isoladamente (Hooks, CI, etc).

### Workflow, Hooks e Commit Message
Como workflow do GIT, esse repositório utiliza o [Feature Branch Workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow).
As mensagems de commit são padronizada via template com informações como tipo (Feature, Bugfix, Patch, Merge) e categoria (Add, Modify, Refactoring, Remove), e a permissão de arquivos, validação de formatação e demais configurações realizadas via hooks.

---

## Client

Repositório: https://github.com/dougaraujos/mercado-livre-client

Aplicação desenvolvida em React + Webpack, utilizando *ES6*.

Para estilização, utiliza CSS Modules + SASS, potencializando a escalabilidade, componentização, isolamento de responsabilidades e melhor organização.

### Inicialização
Executar os seguintes comandos na pasta **client**
1.  Instalar dependências
`npm install`

2.  Iniciar aplicação
`npm start`

### State Management
O gerenciamento de estados da aplicação é realizado pelos próprios componentes de interface. No entanto, para implementação de complexidade e features integradas, recomenda-se a utilização de arquiteturas com nível de abstração e centralização do fluxo de dados (por exemplo, Flux).

---

## Server

Repositório: https://github.com/dougaraujos/mercado-livre-server

Aplicação desenvolvida em Node + Express, utilizando *ES6*.

### Inicialização
Executar os seguintes comandos na pasta **server**
1.  Instalar dependências 
`npm install`

2.  Iniciar aplicação
`npm start`
