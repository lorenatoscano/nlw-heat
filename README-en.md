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
  <a href="#about">About</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#used-technologies">Used technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#how-to-run">How to run?</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#license-and-author">License and Author</a>
</p>

![cover](.github/cover.png?style=flat)

## About
This project was developed during the Next Level Week #7 of the [Rocketseat](https://rocketseat.com.br/)'s Impulse  trail. It consists of a real-time message delivering and receiving platform with GitHub authentication, contextualized for the [DoWhile 2021](https://dowhile.io/) event.

### Access the project layouts:
- [Web Layout](https://www.figma.com/file/OosiXyAUYmnwvTxV9t2xIr/%5BNLW-Heat---Mission%3A-Impulse%5D-DoWhile2021-(Community)?node-id=0%3A1)
- [Mobile Layout](https://www.figma.com/file/OosiXyAUYmnwvTxV9t2xIr/%5BNLW-Heat---Mission%3A-Impulse%5D-DoWhile2021-(Community)?node-id=61419%3A92)

### Status:
- Lesson 1 - Backend with Node - Done ✅
- Lesson 2 - Web with React - Done ✅
- Lesson 3 - Mobile with React Native - Done ✅
- Lesson 4 - Backend extension with Elixir - In progress 🚧

## Used technologies

This project was developed using the following technologies:

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

## How to run?

Run the following commands on your terminal:

```bash
# Clone the repository
$ git clone https://github.com/lorenatoscano/nlw-heat.git

# Change to the repository directory
$ cd nlw-heat
```

### 📦 API

> Observation: This project requires authentication via OAuth with GitHub. Create your OAuth app [here](https://github.com/settings/developers). 

```bash
# Change to the backend directory
$ cd backend

# Make a copy of the `.env.example` file to `.env` and then fill it with your GitHub credentials
$ cp .env.example .env

# Install the dependencies
$ yarn

# Run the migrations
$ yarn prisma migrate dev

# Start the server
$ yarn dev
```

Access the API at http://localhost:4000.

### 💻 Web
> In order to use the server with the web aplication, remember to set your OAuth App's "Authorization callback URL" field to http://localhost:3000.

```bash
# Change to the web application directory
$ cd web

# Install the dependencies
$ yarn

# Run the application
$ yarn start
```
Access the http://localhost:3000/ address on your browser to se the result.

### 📱 Mobile
> In order to use the server with the mobile aplication, it's required to create an account on [Expo](https://expo.dev/), create a project named `nlwheatapp` and set your OAuth App's "Homepage URL" and "Authorization callback URL" fields to https://auth.expo.io/@[your-username-here]/nlwheatapp

```bash
# Change to the mobile application directory
$ cd mobile

# Install the dependencies
$ yarn

# Run the application
$ expo start
```
To see the result of the mobile version, you need to either have the [Expo](https://play.google.com/store/apps/details?id=host.exp.exponent) app installed on a smartphone or have an Android/IOS emulator so that you can install the app on it.

After you run the aplication, read the QRCode through the app.

## License and Author

This project is under the MIT License. Se the [LICENSE](https://github.com/lorenatoscano/nlw-heat/main/LICENSE) file for more details.

Made with :purple_heart: by [Lorena Toscano](https://github.com/lorenatoscano).


[![Linkedin Badge](https://img.shields.io/badge/-Lorena_Toscano-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/lorena-toscano-243432183/)](https://www.linkedin.com/in/lorena-toscano-243432183/)
