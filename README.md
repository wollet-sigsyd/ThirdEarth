# ThirdEarth
Urbit Hosting Platform

# ThirdEarth Docs

## O que é a ThirdEarth
	
- Inicialmente: plataforma para venda de identidades (planetas) e hospedagem do sistema operacional ponto a ponto, Urbit.
- No futuro: ser o futuro da hospedagem para o Urbit, oferecendo uma maneira fácil de gerenciamento do sistema, total suporte para o usuário e interface de usuário com principais funcionalidades automatizadas para o usuário (exibição e reset de código de acesso, automação de geração e hospedagem de luas, etc.).


## Escolha da Stack

- Base de dados: Postgres
- Javascript: React, Express, Node.js, jwt, [knex ou typeORM], passport, [nodemailer ou sendgrid]

## Configuração IDE

- EsLint
- Prettier
- editorConfig (opcional)

## Estrutura de diretório para backend

```
└───models
└───database
|  │
|  └───migration
|  │  
|  └───config.js
└───customFunctions
└───controllers
└───middlewares
│   routes.js
│   app.js
│   server.js
```
 
## Estrutura de diretório para o front

```
└───public
└───src
|   │
|   └───assets
│   |   |
|   |   └───img
│   |   |
|   |   └───ico
│   |   |
|   |   └───styles
|   │   |   |
|   |   |   |   globalStyles.js 
|   │
|   └───components
│   |   |
|   |   └───Menu
|   │   |   |
|   |   |   |   Menu.jsx
|   |   |   |   styles.js
|   │
|   └───pages
│   |   |
|   |   └───Home
|   │   |   |
|   |   |   |   Home.jsx
|   |   |   |   styles.js
|   │
|   └───context
|   │
|   └───api
|   │   |
|   |   |   apiConn.js
│  
|   App.js
|   index.js
```

## Requisitos funcionais da plataforma

- Cadastro
- Confirmação de email
- Login
- Escolha do produto (planeta)
- Pagamentos
    - Email de confirmação de compra
    - Estrela gera planeta
    - API busca o keyfile
    - Realiza hospedagem
    - Configurar subdominio
    - Envio do link para acesso com código
