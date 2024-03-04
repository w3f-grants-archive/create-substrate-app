# Create Substrate App
***
`create-substrate-app` is a command-line tool that simplifies the process of starting a new decentralized web app
creation connected to a Substrate based chain. It allows developers to quickly bootstrap a new project with templates
for React, Vue, and Angular, getting you started with Substrate DApp development in no time.

## Prerequisites
Before you begin, ensure you have the following installed on your system:
- Node.js (v12.x or later)
- npm (v6.x or later)

## Getting Started
To create a new app, run the following command in your terminal:
```sh
npx create-substrate-app my-app
```
Replace `my-app` with the name of your project. This command creates a new directory named `my-app`, initializes a new
project, and installs dependencies automatically.

## Selecting a Frontend Framework
During the setup process, you will be prompted to choose a frontend framework from the following options:
- React
- Vue
- Angular

The tool will then generate a project template based on your selection.

## Running Your Application
Navigate to your project directory:
```sh
cd my-app
```
To start the application, run:
```sh
npm start
```

All of the templates are based on the starter templates provided by respective frameworks:
- React: [create-react-app](https://github.com/facebook/create-react-app)
- Vue: [create-vue](https://github.com/vuejs/create-vue)
- Angular: [angular-cli](https://github.com/angular/angular-cli)

No opinionated assumptions have been made regarding state management, allowing the user to freely choose their
preferred tool.

## License
`create-substrate-app` is open source software licensed as [Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0)
