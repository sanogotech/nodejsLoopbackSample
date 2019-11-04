# nodejsLoopbackSample
REST API With  Loopback  NodeJS Framework

# Direct: Start Project /start the application using:
$  npm start


Visit http://127.0.0.1:3000/hello to see Hello world!

#-------- Steps End to End ------------------
## Step 1  / Install  Node.js

https://nodejs.org/en/download/

## Step 2 / Install LoopBack 4 CLI:

$ npm install  --no-optional -g @loopback/cli


## Step 3  /Create a new project and Answer the prompts as follows:

$ lb4 app


## SteP4 / Starting the project
$ npm start
In a browser, visit http://127.0.0.1:3000/ping

## Step 5 /Add your own controller :

 $ lb4 controller
 
- Paste the following contents into the file /src/controllers/hello.controller.ts

import {get} from '@loopback/rest';
export class HelloController {
  @get('/hello')
  hello(): string {
    return 'Hello world!';
  }
}

## Step 6 /Test your application:

start the application using:
$  npm start

Visit http://127.0.0.1:3000/hello to see Hello world!