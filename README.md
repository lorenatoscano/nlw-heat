 <p align="center">
   <a href="https://github.com/lorenatoscano/nlw-heat/blob/main/README-en.md">English</a>&nbsp;&nbsp;&nbsp;•&nbsp;&nbsp;
   <a href="https://github.com/lorenatoscano/nlw-heat/blob/main/README.md">Português (Brasil)</a>
</p>

<p align="center">
   <img src="./.github/logo.svg" alt="DoWhile 2021" width="300"/>
</p>

<p align="center">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/lorenatoscano/nlw-heat.svg?color=FF008E">

  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/lorenatoscano/nlw-heat.svg?color=FF008E">
  
  <a href="https://github.com/lorenatoscano/nlw-heat/commits/main">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/lorenatoscano/nlw-heat.svg?color=FF008E">
  </a>

  <img alt="GitHub" src="https://img.shields.io/github/license/lorenatoscano/nlw-heat?color=FF008E">
</p>

<p align="center">
  <a href="#sobre">Sobre</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#tecnologias-utilizadas">Tecnologias utilizadas</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#como-rodar">Como rodar?</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#licença-e-autora">Licença e Autora</a>
</p>

![cover](.github/cover.png?style=flat)

## Sobre
Projeto desenvolvido durante a trilha Impulse do Next Level Week #7 da [Rocketseat](https://rocketseat.com.br/). Consiste numa plataforma de envio e recebimento de mensagens em tempo real com autenticação pelo Github, contextualizada para o evento [DoWhile 2021](https://dowhile.io/)

### Acesse os layouts do projeto:
- [Layout Web](https://www.figma.com/file/OosiXyAUYmnwvTxV9t2xIr/%5BNLW-Heat---Mission%3A-Impulse%5D-DoWhile2021-(Community)?node-id=0%3A1)
- [Layout Mobile](https://www.figma.com/file/OosiXyAUYmnwvTxV9t2xIr/%5BNLW-Heat---Mission%3A-Impulse%5D-DoWhile2021-(Community)?node-id=61419%3A92)

### Status:
- Aula 1 - Backend em Node - Concluída ✅
- Aula 2 - Web em React - Concluída ✅
- Aula 3 - Mobile em React Native - Concluída ✅
- Aula 4 - Extensão do Backend em Elixir - Em construção 🚧

## Tecnologias utilizadas

Este projeto foi desenvolvido utilizando as seguintes tecnologias:

### 📦 API
- [Node.js](https://nodejs.org/en/)
- [TypeScript](https://www.typescriptlang.org/)
- [Express](https://expressjs.com/pt-br/)
- [Prisma](https://www.prisma.io/)
- [JSON Web Token](https://jwt.io/)
- [Socket.IO](https://socket.io/)

### 💻 Web
- [ReactJS](https://reactjs.org/)
- [Typescript](https://www.typescriptlang.org/)
- [Vite](https://vitejs.dev/)
- [Sass](https://sass-lang.com/)

### 📱 Mobile
- [React Native](https://reactnative.dev/)
- [Expo](https://expo.dev/)
- [Moti](https://moti.fyi/installation)

## Como rodar?

Execute os seguintes comandos no seu terminal:

```bash
# Clone o repositório
$ git clone https://github.com/lorenatoscano/nlw-heat.git

# Entre no repositório
$ cd nlw-heat
```

### 📦 API

> Obs.: Nesse projeto temos autenticação via OAuth com o GitHub. Crie seu OAuth app [aqui](https://github.com/settings/developers). 

```bash
# Entre na pasta do backend
$ cd backend

# Faça uma copia do arquivo `.env.example` para `.env` e preencha com as suas credenciais do GitHub
$ cp .env.example .env

# Instale as dependências
$ yarn

# Execute as migrations
$ yarn prisma migrate dev

# Inicie o servidor
$ yarn dev
```

Acesse a API em http://localhost:4000

### 💻 Web
> Para utilizar o servidor com a aplicação web, lembre-se de colocar http://localhost:3000 no campo "Authorization callback URL" do seu OAuth App

```bash
# Entre na pasta web
$ cd web

# Instale as dependências
$ yarn

# Execute a aplicação
$ yarn start
```
Acesse em seu navegador http://localhost:3000/ para ver o resultado.

### 📱 Mobile
> Para utilizar o servidor com a aplicação mobile, é necessário criar uma conta no [Expo](https://expo.dev/), criar um projeto com o nome `nlwheatapp` e colocar https://auth.expo.io/@[seu-user]/nlwheatapp nos campos "Homepage URL" e "Authorization callback URL" do seu OAuth App

```bash
# Entre na pasta mobile
$ cd mobile

# Instale as dependências
$ yarn

# Execute a aplicação
$ expo start
```

Para ver o resultado da versão mobile você precisa de um smartphone com o aplicativo [Expo](https://play.google.com/store/apps/details?id=host.exp.exponent) instalado ou um emulador android/ios.

Depois de executar a aplicação, leia o QRCode pelo aplicativo.


## Licença e Autora

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](https://github.com/lorenatoscano/nlw-heat/main/LICENSE) para mais detalhes.

Feito com :purple_heart: por [Lorena Toscano](https://github.com/lorenatoscano).


[![Linkedin Badge](https://img.shields.io/badge/-Lorena_Toscano-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/lorena-toscano-243432183/)](https://www.linkedin.com/in/lorena-toscano-243432183/)
