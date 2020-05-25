# Yeoman Sample Project

[Yeoman](https://yeoman.io/) is an open source client-side scaffolding tool for web applications. Yeoman runs as a command-line interface written for Node.js and combines several functions into one place, such as generating a starter template, managing dependencies, running unit tests, providing a local development server, and optimizing production code for deployment.

This repo contains sample project made for learning the implementation of yeoman and bootstrap theme rolling. 

Open and view the Project using the `.zip` file provided or at my [Github Repository](https://github.com/madhur-taneja/Yeoman-Sample-Project)

## Table of Contents
- [Getting Started](#getting-started)
	- [Tools Required](#tools-required)
	- [Installation](#installation)
- [Development](#development)
  - [Steps To Build An App Using Yeoman](#steps-to-build-an-app-using-yeoman)
  - [Steps For Adding Bootstrap Theme Rolling](#steps-for-adding-bootstrap-theme-rolling)
- [References](#references)

To do the same, follow the below mentioned steps:

## Getting Started

### Tools Required
You would require the following tools:

* [Node.js](https://nodejs.org/en/download/).
* [npm](https://www.npmjs.com/)
* A text-editor of your choice.

### Installation

* Make sure you have setup node and npm.

* Open CMD and run the following command to globally install yeoman:
  ```
  npm install -g yo
  ```

## Development

### Steps To Build An App Using Yeoman:

> After setting up yeoman, install a generator for the project according to the requirements. Search for them from [here](http://yeoman.io/generators/). I have used [generator-webapp](https://github.com/yeoman/generator-webapp). Use the following command:

* `npm install -g generator-webapp`

> To scaffold a new project, run:

* `yo webapp`

> Most generators will ask a series of questions to customize the new project. To see which options are available, use the help command:

* `yo webapp --help`

> A lot of generators rely on build systems (like Grunt or Gulp), and package managers (like npm and Bower). Make sure to visit the generator’s site to learn about running and maintaining the new app. Easily access a generator’s home page by running:

* `npm home generator-webapp`

> Most issues can be found by running:

* `yo doctor`

### Steps For Adding Bootstrap Theme Rolling:

> Open [Bootstrap Build](https://bootstrap.build/app/v4.1.1/) or any other website that provides bootstrap custom theme builder. </br>
  Adjust the values according to your need. </br>
  Export the file and link it to your project. </br>
  
## References

* Yeoman tutorial by [Learn Code Academy](https://www.youtube.com/watch?v=gKiaLSJW5xI)
* [Yeoman CodeLab](https://yeoman.io/codelab/)
* Learn more about Bootstrap theming [here](https://getbootstrap.com/docs/4.0/getting-started/theming/). </br>
