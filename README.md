
# [Timestamp Microservice](https://www.freecodecamp.org/learn/apis-and-microservices/apis-and-microservices-projects/timestamp-microservice)

### About the project
This project is an assignment project created by FCC for APIs and Microservices Certification.

This microservice returns a Timestamp in JSON format. It could be used in two ways.
* a request to `/api/timestamp/` return the current time.
* a request to `/api/timestamp/:date?` return a timestamp based on the parameter. It accepts both valid date string and unix timestamp.

### Getting Started

[Express](https://expressjs.com/) is used as the Node.js web application framework in this project. See [hello-world example](https://expressjs.com/en/starter/hello-world.html).

#### Installing Node and NPM
This project depends on Nodejs and Node Package Manager (NPM). To install Node, go to https://nodejs.org and select the appropriate installation package depending on your computer's platform (Windows, MacOS or Linux).

`Note: On Windows machines, you may need to configure your PATH environmental variable in case you forgot to turn on the add to PATH during the installation steps.`

#### Verifying the Node Installation
To ensure that your NodeJS setup is working correctly, open the terminal and type the following to check for the version of Node and NPM
```
$ node -v
$ npm -v
```

#### Installing project dependencies
This project uses NPM to manage software dependencies. NPM Relies on the package.json file. To install dependencies, open the terminal, cd to the project directory and run:
```
$ npm install
```

### Running the server

To run locally, cd to the project directory and type the following command:
```
$ node server.js
```
Then, load http://localhost:{port}/ in a browser to see the output.

**NOTE:** A default port is not set to for this project. Please see terminal for port number, or set an environmental variable `PORT=`. 