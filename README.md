# Formacorpus

This is code repository for Formacorpus and its version is 0.0.0. 

This is the webpage project for the Formacorpus Gym. It is going to have a system where people can access they daily training schedule.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. If you want to do a pull request, feel free to do it as you want :) 

### Prerequisites

Before start the instructions you should have git, nodejs, mongodb, typescript, nodemon, terminal, nestjs and angular cli installed globally in your computer.

### Installing

After doing the prerequisites you should run the command below in your terminal at any folder you would like.

```
git clone https://github.com/lukasfialho/formacorpus.git
```

After it, either in app's and server's folder, run the command below to install all dependencies of the project.

```
npm install
```

## Running the development mode

### Angular [app]

In hiro-app's folder you should run the command bellow and the angular cli will automatically open the stack's web application in your default browser.

```
ng serve --open
```

If you do not want it to open automatically you should run the command below.

```
ng serve
```

### Nodejs [server]

In server's folder you should open another tab of your terminal and run the following command to run the NestJS to make the server start in the development mode at http://localhost:3000/:

```
npm run start:dev
```

<!-- ## Documentation

After running the project locally you will be able to access its documentation at 

```
http://localhost:3000/docServer/v0/
``` 

for the backend and at

```
http://localhost:3000/docFront/v0/
```

for the frontend. 

### Updating the Documentation

To update the documentation you should have installed the compodoc globally in you computer. After it you can run the command below at both folders stack and server:

```
npm run doc
```
-->

## Built With

* [Angular](https://angular.io/) - Used to create the application frontend
* [Node.js](https://nodejs.org/en/) - Used to create the server and its APIs
* [MongoDB](https://www.mongodb.com/) - Used as the main database
* [Typescript](https://www.typescriptlang.org/) - Used the write all the codes and compile it to Javascript
* [NestJS](https://docs.nestjs.com) - Nest is a progressive Nodejs framework for building efficient, reliable and scalable server-side applications
<!-- * [CompoDoc](https://compodoc.app/) - Used to create automatically the project documentation -->




## Versioning

We use [SemVer](http://semver.org/) for versioning. For the past few versions it is not being used properly but we are working on it.

## Authors

* **Lukas Camargo** - *Fullstack Developer*

## License

Code and documentation copyright 2018 the Formacorpus.
