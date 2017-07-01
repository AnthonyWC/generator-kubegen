# Yeoman generator for you Kubernetes boilerplate code

kubegen is a tool that aims to simplify your Kubernetes day-to-day, writing the boilerplate code for you and letting you focus on the important things.

kubegen is a [Yeoman](http://yeoman.io) generator, so you'll need to have [NodeJS](https://nodejs.org/) installed.

# Installation

To install kubegen, you need to execute the following command:

```bash
npm install generator-kubegen
```

# Usage

Quite easy!

```bash
yo kubegen
 |  |/  / |  |  |  | |   _  \  |   ____| /  _____||   ____||  \ |  |
 |  '  /  |  |  |  | |  |_)  | |  |__   |  |  __  |  |__   |   \|  |
 |    <   |  |  |  | |   _  <  |   __|  |  | |_ | |   __|  |  . `  |
 |  .  \  |  `--'  | |  |_)  | |  |____ |  |__| | |  |____ |  |\   |
 |__|\__\  \______/  |______/  |_______| \______| |_______||__| \__|

Welcome to Kubernetes Generator (kubegen)!
? How the service should be named? nginx
? In which Namespace should be deployed? default
? Which type of Pod controller mechanism whould you like to use? Deployment
? Which image should we use? nginx:latest
? How much container replicas should be created? 1
? Would like to expose the service out of the cluster? yes
? Choose your expose mechanism? Ingress
? Does the service have a hostname?
? Ingress root path? /
? Service port? 80
   create deployment.yml
   create service.yml
   create ingress.yml
```

# Contributing

Contribution is welcome! Just:

- Fork this project
- install the NPM dependencies:

```bash
npm install
```

- Link this folder to npm

```bash
npm link
/usr/local/lib/node_modules/generator-kubegen -> /Users/User/generator-kubegen
```

- Edit the project with your favorite text editor or tool

# Debugging

For your conveniente, this project comes with a pre-built configuration to debug the solution with [Visual Studio Code](https://code.visualstudio.com). Just go to the "Debug" menu on the left, select "Yeoman generator" in the dropdown (beside "play button") and then click "play" to start debugging.

![debug with VSCode](docs/debug.png)