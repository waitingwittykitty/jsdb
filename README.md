# JSDB Server

You can launch your app without any extra db red tapes.

## How to start

Install packages

```shell
npm i @jsdb/server
```

Create .env file

```dotenv
# Used to sign jwt tokens
JWT_SECRET="SUPER_SECRET_KEY"

# Nodejs server port
PORT=3001

# Max requests per minute from the same IP
RATE_LIMIT=10000
```

Run your server

```shell
npm start
```
