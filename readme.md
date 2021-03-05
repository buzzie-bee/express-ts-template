# Express Typescript Jest EsLint Prettier Template

A personal boilerplate template to begin building express applications.

## How to use

### Installation

To use it and initialise a project use

`git clone --depth 1 https://github.com/buzzie-bee/express-ts-boilerplate {PROJECT_NAME}`

`rm -rf .git` to delete the git history from this template

`git init` to initialise a new git repo

`npm install` to install npm packages

Make sure to create your own .env file with your environment variables. Use the .env file as a template.

### Troubleshooting

It's unlikely but still possible that the package.lock file may contain packages that are not compatible with your system due to this being developed on ubuntu so delete the package.lock and run `npm install` again if you get errors.

### Scripts

`npm run test` ---- This runs the jest tests found in the src folder

`npm run test` ---- Runs jest tests in watch mode

`npm run build` ---- Deletes the dist folder and tsc compiles the src contents back into it

`npm run start` ---- Runs Build and runs /dist/index.js

`npm run dev:server` ---- Runs ts-node dev in transpile only mode

## Packages

### Production packages:

- express
- cors
- helmet
- dotenv
- rimraf

### Dev packages

- typescript
- ts-node-dev
- eslint
- eslint-airbnb-typescript
- prettier
- jest
- ts-jest
- supertest

## Folder structure

```
/src
  /common
    /exceptions
    /helpers
  /config
  /middleware
  /routes
```
