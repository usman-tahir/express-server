# Express Server

### Overview
This Express server has been set up with TypeScript 2, and can be run locally to host your application. It utilizes a `tsconfig.json` file to compile any application files in the `app/` directory, and manages other configurations in the generated `typings/` directory.

### Installation
To begin, navigate to the root folder of this project and run `npm install`. Once this is done, run `typings install` to install the `typings` definitions (Make sure to have `typings` installed globally on your machine).

When that is done, run `npm start` to compile your TypeScript files (`app/**/*.ts`) and have them deployed to the `dist/` directory, and to start the server itself on port 3000 (`http://localhost:3000/welcome`). Since a sample `WelcomeController` is being used, you will need to navigate to the URL specified above to use its endpoints for sample testing.

### Usage in your Application
Any application files can be served from the `dist/` directory, once you build your project with `npm start`. This allows for the server that has been created to be extended further, to suit your specific needs. From Single Page Applications (SPAs), to full fledged RESTful APIs, this base project can be extended in any direction.

### Next Steps
This project can be extended with any front-end development stack, and can be extended in the server capabilities it offers, as well.