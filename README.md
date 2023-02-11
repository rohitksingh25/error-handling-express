# Error Handling in express

This repository contains sample code on how to do error handling with the Node.js [express](https://expressjs.com/) framework.

## Session implementation with express.js and express-session

This repository illustrates how to handle expected errors in a DRY way in express and how to not expose any internal structure in case of unexpected errors.

## Running this project

Run

```
npm install
```

to install the project's dependencies.

Execute the `dev` script to start up your server.

```
npm run dev
```

## API

### POST /tweet

Expected payload

```
{
    "msg": "my tweet message"
}
```
