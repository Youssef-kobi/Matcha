<h1 align="center">
  <br>
  <a href="https://github.com/Youssef-kobi/Matcha"><img src="https://user-images.githubusercontent.com/52678976/231610377-a2030b73-75a7-42c4-b7ed-f678cdc03df2.png" alt="Matcha" width="200"></a>

  <br>
  Dating Web App
  <br>
</h1>

<h4 align="center">A Vue.js dating web application with real-time chat and geolocation features</h4>

<p align="center">
 <a href="https://img.shields.io/npm/v/npm?style=plastic"><img src="https://img.shields.io/npm/v/npm?style=plastic" alt="npm version" height="18"></a>
</p>

<p align="center">
  <a href="#introduction">Introduction</a> •
  <a href="#key-features">Key Features</a> •
  <a href="#how-to-use">How To Use</a> •
  <a href="#license">License</a>
</p>

<!-- ![screenshot](https://raw.githubusercontent.com/amitmerchant1990/electron-markdownify/master/app/img/markdownify.gif) -->

## Introduction

Matcha is a Vue.js dating web application with real-time chat and geolocation features. The application is built with the following technologies:

- **Vue.js** for the front-end
  - **Vuex** for state management
  - **Vue Router** for routing
  - **Axios** for API calls
- **Node.js** and **Express.js** for the back-end
- **MongoDB** as a NoSQL database
- **Socket.io** for real-time, bi-directional communication between web clients and servers.
- **Bcrypt.js** for password hashing and salting
- **JSON Web Tokens (JWT)** for authentication

## Key Features

<img align="right"  width="220" height="400" src="https://raw.githubusercontent.com/Youssef-kobi/Matcha/main/client/src/assets/Matcha2.png" alt="Matcha Screenshots"/>

- User authentication and authorization
- Profile creation and editing
- Search and filter user profiles
- Real-time chat with other users
- Real-time geolocation tracking of other users
- Interactions between users (like, unlike, block, report)
- Notifications of profile likes, messages, and interactions
- Responsive design for mobile and desktop
- Client-side and server-side validation

## TO-DO

- Implement email verification for user registration
- Add the ability to upload photos
- Implement third-party authentication (e.g. Google, Facebook)

## How To Use

To clone and run this application, you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
$ git clone https://github.com/Youssef-kobi/Matcha

# Go into the repository
$ cd Matcha

# Install dependencies
$ npm install

# Start the server
$ npm run server

# Start the client
$ npm run client

# Start both server and client
$ npm run dev
```


> **Note**
> If you're using Linux Bash for Windows, [see this guide](https://www.howtogeek.com/261575/how-to-run-graphical-linux-desktop-applications-from-windows-10s-bash-shell/) or use `node` from the command prompt.

## License

MIT
