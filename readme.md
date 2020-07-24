# Amigo Secreto Online

Essa aplicação é um desafio da Adireto. A aplicação permite um CRUD de participantes e a realização de um sorteio de amigo secreto, com envio de emails para os participates.

## Stack Utilizada

- Express
- Mongoose + MongoDB
- React
- Redux
- Outras libs

## Como utilizar

Parar rodar a API é necessário ter uma versão recendo do Node e NPM instalado. Depois utilizar os seguintes comandos:
`cd backend`
`npm install`
`node server.js`
Também é necessário configurar um arquivo .env com as seguintes variáveis de ambiente:

- MONGODB_URI
- GMAIL_HOST
- GMAIL_PORT
- GMAIL_USER
- GMAIL_PASS

Para roder o app você precisa abrir outra janela no terminal, navegar até a pasta root do projeto e executar os seguintes comandos:
`cd frontend`
`npm install`
`npm start`

## Versão online

É possível acessar a versão live do projeto no link [aqui](https://rest-countries-bnrosa.netlify.app/)