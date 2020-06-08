<div align="center">
    <img src="https://res.cloudinary.com/dr05turuf/image/upload/v1591570268/rocketseat/next-level-week/ecoleta_mh9pws.svg" width="300px"/>
</div>

<h2 align="center">
   ♻️ Ecoleta ♻️
   </br>
   </br>
   <img src="https://res.cloudinary.com/dr05turuf/image/upload/v1591577795/rocketseat/next-level-week/banner_xfbdzk.png"/>
</h2>

<p align="center">
  <a href="#computer-project">Project</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#rocket-built-with">Built with</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#information_source-how-to-run">How to run</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-license">License</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#mailbox_with_mail-get-in-touch">Get in touch</a>
  </p>

## :computer: Project

Ecoleta is an application that aims to help people find places that collect specific types of waste, encouraging people to recycle more.

<p align="center">
  <img src="https://res.cloudinary.com/dr05turuf/image/upload/v1591577800/rocketseat/next-level-week/web_tlqfsm.svg"/>
  <img src="https://res.cloudinary.com/dr05turuf/image/upload/v1591577797/rocketseat/next-level-week/home-mobile_pcpudo.png" width="250px"/>
</p>

## :rocket: Built with

This project was developed with the following technologies:

- [Node.js](https://nodejs.org/)
- [ReactJS](https://reactjs.org/)
- [React Native](https://facebook.github.io/react-native/)
- [TypeScript](https://github.com/microsoft/TypeScript)
- [Express](https://expressjs.com/)
- [React Navigation](https://reactnavigation.org/)
- [React-icons](https://react-icons.netlify.com/)
- [Axios](https://github.com/axios/axios)
- [VS Code](https://code.visualstudio.com/)

## :information_source: How to run

### Requirements

To run the application you will need:

- [Git](https://git-scm.com)
- [Node](https://nodejs.org/)
- [Yarn](https://yarnpkg.com/)

### Backend

Now clone the repository and install the dependencies.

```bash
# to clone the repository
$ git clone https://github.com/felsantiago/next-level-week.git

# go into the backend folder
$ cd next-level-week/nlw-01/server

#install the backend dependencies
$ yarn

```

In order to connect to the database, you will need to enter the access informations into a ormconfig.json. You can find more about it [here](https://typeorm.io/#/using-ormconfig).

```bash
# run migrations
$ yarn knex:migrate
$ yarn knex:seed

# run api
$ yarn dev:server
```

### Frontend

```bash
# in another tab of the terminal install the frontend dependencies and run it
$ cd next-level-week/nlw-01/web
$ yarn
$ yarn start
```

### Mobile

The Application was developed using Expo. It is a free and open source toolchain built around React Native to facilitate the process of running and testing applications. [Click here](https://expo.io/learn) to get start with Expo.

```bash
# install the dependencies
cd mobile
yarn
```

In order to run the application on your device, you need to change the ip config.

```javascript
  baseURL: 'http://192.168.0.118:3333',
```

replace 192.168.0.118 with your machine's ip.

Now with everything on place, run the application.

```bash

# to run the app
yarn start

```

Expo will open a page in your browser, scan the QRcode on the page and wait for the app to load.

> The Application was developed and tested on Iphone 6s and Android Studio Emulator.

## :memo: License

This project is under the MIT license. See the [LICENSE](https://github.com/felsantiago/next-level-week/blob/master/LICENSE) for more information

## :mailbox_with_mail: Get in touch!

<p>

  <a href="https://github.com/felsantiago" target="_blank" >
    <img alt="Github - Felipe Santiago" src="https://img.shields.io/badge/Github--%23F8952D?style=social&logo=github">
  </a>
  <a href="https://www.linkedin.com/in/felipe-santiago-a7706418a/" target="_blank" >
    <img alt="Linkedin - Felipe Santiago" src="https://img.shields.io/badge/Linkedin--%23F8952D?style=social&logo=linkedin">
  </a>
  <a href="mailto:fepuss@gmail.com" target="_blank" >
    <img alt="Email - Felipe Santiago" src="https://img.shields.io/badge/Email--%23F8952D?style=social&logo=gmail">
  </a>
  <a href="https://api.whatsapp.com/send?phone=5588997143829"
        target="_blank" >
    <img alt="Fale comigo no whatsapp - Felipe Santiago" src="https://img.shields.io/badge/Whatsapp--%23F8952D?style=social&logo=whatsapp">
  </a>
</p>

---

Made with ❤️ by Felipe Santiago.
