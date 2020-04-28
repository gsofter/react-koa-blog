# React-Koa-Blog

This project is based on koa for backend and react.js for frontend.

## Getting Started

### Prerequisites

```
node version > 10.04 LTS
```

For database management, setup mongodb. <br />

#### MacOS

```shell
$ brew update
$ brew install mongodb
$ brew services start mongodb
```

#### Windows

You can download [here](https://www.mongodb.com/download-center/community)

#### Linux

You can see detailed guide [here](https://www.mongodb.com/download-center/community)

### Database configuration

```
PORT=<YOUR MONGODB PORT>
MONGO_URI=<YOUR MONGODB HOST>
JWT_SECRET=<YOUR JWT SECURITY KEY>
```

### Running Node(Koa) Server

```shell
cd blog-backend/
npm install
npm start
```

### Running Frontend on Local

```shell
cd blog-frontend/
npm install
npm start
```
