# React Datta Able PRO

**Datta Able** is a premium **React Dashboard** that provides a colorful and modern design. Datta Able React PRO is the most stylised React Free Admin Template, around all other admin templates in the market. It comes with high feature-rich pages and components with fully developer-centric code. The product comes with a simple JWT authentication flow: login/register/logout.

<br />

> Features

- Modern aesthetics UI design - Designed by [CodedThemes](https://codedthemes.com/)
- React, Redux, Redux-persist
- Authentication: JWT Login/Register/Logout
- For a complete full-stack experience, this UI can be used with:
  - [Django API Server](https://docs.appseed.us/boilerplate-code/api-server/django) - open-source product
  - [Flask API Server](https://docs.appseed.us/boilerplate-code/api-server/flask) - open-source product
  - [Node JS API Server](https://docs.appseed.us/boilerplate-code/api-server/node-js) - open-source product / Typescript / SQLite / TypeORM / Joy for validation
  - [Node JS API Server PRO](https://github.com/app-generator/api-server-nodejs-pro) - **commercial product**
      - SQLite / TypeORM / Joy / Docker
      - MongoDB / Mongoose / Joy Docker (separate branch, same project)

<br />

![React Nodejs Datta Able - Open-source full-stack seed project crafted by CodedThemes and AppSeed.](https://user-images.githubusercontent.com/51070104/126295682-6e89cdd8-455f-4f44-bb3c-0302d02c34a2.png)

<br />

## How to use it

To use the product Node JS (>= 12.x) is required and GIT to clone/download the project from the public repository.

**Step #1** - Clone the project

```bash
$ git clone https://github.com/app-generator/priv-react-datta-able-dashboard-pro.git
$ cd priv-react-datta-able-dashboard-pro
```

<br >

**Step #2** - Install dependencies via NPM or yarn

```bash
$ npm i
// OR
$ yarn
```

<br />

**Step #3** - Start in development mode

```bash
$ npm run start 
// OR
$ yarn start
```

<br />

## Configure the backend server

The product comes with a usable JWT Authentication flow that provides only the basic requests: login/logout/register. 

**API Server URL** - `src/config/constant.js` 

```javascript
const config = {
    ...
    API_SERVER: 'http://localhost:5000/api/'  // <-- The magic line
};
```

<br />

> **API Descriptor** 

The product uses implements a **Unified API definition** exposed by all API servers crafted by AppSeed. For more information, please access the official documentation:

- All [API Servers](https://docs.appseed.us/boilerplate-code/api-server) - the full index
- [Unified API Definition](https://docs.appseed.us/boilerplate-code/api-server/api-unified-definition) - methods implemented accross all servers


<br />

---
React Datta Able PRO - Provided by [CodedThemes](https://codedthemes.com/) and **AppSeed [App Generator](https://appseed.us/app-generator)**.
