&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[![language](https://img.shields.io/github/languages/top/PraneshASP/node-authentication-jwt-mongodb)]("https://github.com/praneshasp/node-authentication-jwt-mongodb")
[![vulnerability](https://img.shields.io/snyk/vulnerabilities/github/PraneshASP/node-authentication-jwt-mongodb)](https://github.com/PraneshASP/node-authentication-jwt-mongodb)
[![repo size](https://img.shields.io/github/repo-size/PraneshASP/node-authentication-jwt-mongodb)](https://github.com/PraneshASP/node-authentication-jwt-mongodb)
[![node version](https://img.shields.io/node/v/npm)](https://github.com/PraneshASP/node-authentication-jwt-mongodb)
[![npm version](https://img.shields.io/npm/v/npm)](https://github.com/PraneshASP/node-authentication-jwt-mongodb)

<!-- PROJECT LOGO -->
<br />
<p align="center">

  <h3 align="center">Simple and secure REST API for User Authentication!</h3>

  <p align="center">
    <br />
    <a href="https://pranesh-a-s.medium.com/how-to-build-simple-and-secure-rest-api-for-user-authentication-using-node-js-jwt-and-mongodb-2bdeb3e5427e"><strong>Explore the post »</strong></a>
    <br />
    <br />
    <a href="https://github.com/PraneshASP/node-authentication-jwt-mongodb/issues">Report Bug </a>
    ·
    <a href="https://github.com/PraneshASP/node-authentication-jwt-mongodb/issues"> Request Feature</a>
  </p>
</p>

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
     <li><a href="#license">License</a></li>
    </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

[![Product Name Screen Shot](https://miro.medium.com/max/1920/1*bbN8C4TjOpsuZhMiI_aGow.jpeg)](https://pranesh-a-s.medium.com/how-to-build-simple-and-secure-rest-api-for-user-authentication-using-node-js-jwt-and-mongodb-2bdeb3e5427e)

### What is inside the repo ?

1. User signup/registration with Email verification.
2. User Login.
3. Forgot password and reset password.
4. Session management using JWT (JSON Web Tokens).
5. Bonus: Simple Referral System!

For a more detailed explanation of the code, you can refer to my medium post associated with this project. It is split into two parts.

- [Part I]("https://pranesh-a-s.medium.com/how-to-build-simple-and-secure-rest-api-for-user-authentication-using-node-js-jwt-and-mongodb-2bdeb3e5427e") - Build User signup with email verification, forgot password and reset password.

- ["Part II]("https://pranesh-a-s.medium.com/how-to-build-simple-and-secure-rest-api-for-user-authentication-using-node-js-jwt-and-mongodb-2bdeb3e5427e") - Integrate JWT and Build a Simple Referral System.

### Built With

- [Node.js]() - JavaScript runtime built on Chrome's V8 JavaScript engine.
- [Express.js]() - Minimal and flexible Node.js web application framework
- [MongoDB]() - Cross-platform document-oriented database program

<!-- GETTING STARTED -->

## Getting Started

To get a local copy up and running follow these simple steps :

### Prerequisites

To run this project, you'll need to have the following installed:

- Node.js : [https://nodejs.org](https://nodejs.org)

- npm :
  ```sh
  npm install npm@latest -g
  ```
- MongoDB : [https://mongodb.com](https://mongodb.com) <br>

> You can also use MongoDB Atlas if you prefer.
> <br>

### Installation

1. Register at [https://sendgrid.com] SendGrid and create an API KEY.

2. Clone the repo :
   ```sh
   git clone https://github.com/PraneshASP/node-authentication-jwt-mongodb.git
   ```
3. Install dependencies (use `sudo` if required) :

   ```sh
   npm install
   ```

4. Create `.env` file and configure :
   ```JS
   MONGO_URI = <MONGODB URL>
   JWT_SECRET = <SOME LONG SECURE SECRET>
   SG_APIKEY = <SENDGRID API KEY>  //For sending emails
   ```
5. Start the server :
   ```sh
   npm start
   ```