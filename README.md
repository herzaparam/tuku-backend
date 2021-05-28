<h1 align="center">Backend - Tuku</h1>
<p align="center">
  <a href="https://tukupedia.netlify.app/" target="_blank"><img src="./images/Tuku.png"  width="400" alt="Tuku" border="0" /></a>
</p>

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Built With](#built-with)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Documentation](#documentation)
- [Link](#link)
- [Authors](#authors)

## Introduction

Tuku is an online buying and selling web application that makes it easy to use to shop for various fashion products by offering many fashion categories such as shoes, shirts, trousers, shorts, and jackets. Users can also make online payments quickly, effectively and safely.

## Features

- JWT authentication

- Nodemailer for email verification

- Upload image using multer

- Form validation using joi

- CRUD for all tables required in the application

## Built With

- [ExpressJs](https://expressjs.com/)
- [MySQL](https://www.mysql.com/)
- [JWT](https://jwt.io/)
- [Nodemailer](https://nodemailer.com/)
- [Moment](https://momentjs.com/)
- [Joi](https://www.npmjs.com/package/joi)
- [Bcrypt](https://www.npmjs.com/package/bcrypt)
- [Multer](https://www.npmjs.com/package/multer)
- [Morgan](https://www.npmjs.com/package/morgan)
- [Cors](https://www.npmjs.com/package/cors)
- [Dotenv](https://www.npmjs.com/package/dotenv)
- [Ip](https://www.npmjs.com/package/ip)

## Prerequisites

- [NodeJs](https://nodejs.org/en/download/)
- [XAMPP](https://www.apachefriends.org/index.html)

## Installation

1. Clone the repository

```
git clone https://github.com/chaerulmarwan20/tuku-backend.git
cd tuku-backend
```

2. Install package

```
npm install
```

3. Create a new database with a name `tuku-apps` and import `tuku-apps.sql` from this repository

4. Create .env file

```
# Host & Port
HOST=
PORT=
PORT_FRONTEND=

# Database
DB_HOST=
DB_USER=
DB_PASS=
DB_NAME=tuku-apps

# Secret Key
SECRET_KEY=

# Email
EMAIL_USER=
EMAIL_PASS=
```

5. Run application

```
npm run dev
```

Or

```
npm start
```

## Documentation

[![Run in Postman](https://run.pstmn.io/button.svg)](https://documenter.getpostman.com/view/11970262/TzRPi8hX)

## Link

- :white_check_mark: [`Frontend Tuku`](https://github.com/herzaparam/tuku-backend)
- :rocket: [`Publication`](https://tukupedia.netlify.app/)

## Authors

1. [Wisnu Prasetio](https://github.com/prasetioad) - Frontend - PM
2. [Chaerul Marwan](https://github.com/chaerulmarwan20) - Full Stack - Member
3. [Herza Paramayudhanto](https://github.com/herzaparam) - Backend - Member
4. [Erwin Saputra Sulistio](https://github.com/ErwinSaputraSulistio) - Frontend - Member
5. [Kevin Farid Alpharisy](https://github.com/kevinfaridap) - Frontend - Member
