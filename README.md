# Hello World Web Server

## Usage
This is an example express web server used in an executable tutorial for setting up the dependency manager Renovate bot for an application hosted on Github. The executable tutorial can be found [here](https://github.com/Sebberh/RenovateTutorial).

## Installation

1. Install [NodeJS](https://nodejs.org/en/download/) and npm. When you install NodeJS, npm automatically gets installed on your computer. Check if you have installed NodeJS by running this command in the terminal
```
node -v
```
Check your npm installation by running this command
```
npm -v
```
2. Run `npm install` in the project root, all the necessary dependencies will be installed.
3. To start the server, run `node app.js`.

## Functionality
The express server listens for connections to <http://localhost:3000>. When receiving a connection, the server responds with the message "Hello World!"
