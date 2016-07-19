# Meganote Server

Meganote Server is a REST API for note-taking. It is the backend of the [Meganote](https://github.com/mketiku/meganote).

### Prerequisities
See [Meganote Repo](https://github.com/mketiku/meganote) for prerequisites

### Setup
Copy and edit DOTENV configuration
```
cp .env.example .env
```
Edit the new `.env` file and fill in the variables with appropriate values.

#### Installation
Clone this repo
```sh
$ git clone https://github.com/mketiku/meganote_server.git 
$ cd meganote-server
```
Then
```sh
$ npm install 
```
Then use bcrypt to generate a random key for JWT
```sh
$ node node_modules/bcryptjs/bin/bcrypt blahblahblah
```
### Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.
 tarting the Server

For production
```sh
$ npm start
```
For development
```sh
npm run dev 
```

### Built With
* gulp
* bootstrap
* supervisor
* npm
* nodejs
* angularjs
* mlab.com
* jquery

### Acknowledgments
* Davey Strauss 
* Seth Baugman 