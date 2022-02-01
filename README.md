# Nodejs E-commerce BackendServer (CRUD APIs,JWT Authen,MongoDB)

Shoppy is a React and Node.js based eCommerce App. 

Built with:
* Node.js 
* Express
* Mongoose

## Run Locally
### 1. Install Dependencies
```sh
$ npm install
```

### 2. Create a new env file

Create an `env` file - Set filename`.env.prod` file for production and `.env.dev`for development and save it in the root of your project folder
and add the following configuration details. You can either use the same configuration details for both development and production but it's best to make separate projects. It can be found on your firebase project settings.

```
// SAMPLE CONFIG .env.dev, you should put the actual config details found on your project settings

MONGO_URL=<ATLAS_CLUSTER_CONNECTION_URL>
PORT = <RANDOM>
PASS_SEC = <ANY_STRING_FOR_ENCRYPTION>
JWT_SEC =   <ANY_STRING_FOR_ENCRYPTION>
STRIPE_KEY = <STRIPE_API_SECRET_KEY>
``` 

### 3. Configure the backend server

Follow the instructions from the server-side repository.


### 4. Run development server
```sh 
$ npm start
```

## Build the project
```sh
$ npm run build
```
