# Clean Architecture for node.js

## Folder Structure

```
src
│   main.ts         # Application entry point
└───api             # Express route controllers for all the endpoints of the app
└───config          # Environment variables and configurations
└───loaders         # Split the startup process into modules
└───models          # TypeORM Entities
└───services        # All the business logic is here
└───types           # Type declaration files (d.ts) for Typescript

```

### Install

- Install all dependencies with `yarn install`

### Running in dev mode

- Run `yarn start`
- The server address will be displayed to you as `http://0.0.0.0:5000`

### Building the project and run it

- Run `yarn build` to generated all JavaScript files from the TypeScript sources.
- the builded app located in `dist`.
