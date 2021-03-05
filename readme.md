# Express Typescript Jest EsLint Prettier Template

A personal boilerplate template to begin building express applications.

## How to use

### Installation

To use it and initialise a project use

`git clone https://www.github.com/buzzie-bee/express-ts-boilerplate {PROJECT_NAME}`

`npm install`

### Scripts

`npm run test` ---- This runs the jest tests found in the src folder
`npm run test` ---- Runs jest tests in watch mode
`npm run build` ---- Deletes the dist folder and tsc compiles the src contents back into it
`npm run start` ---- Runs Build and runs /dist/index.js
`npm run dev:server` ---- Runs ts-node dev in transpile only mode

## Packages

### Production packages:

*express
*cors
*helmet
*dotenv
\*rimraf

### Dev packages

*typescript
*ts-node-dev
*eslint
*eslint-airbnb-typescript
*prettier
*jest
*ts-jest
*supertest

## Folder structure

/src
/common
/exceptions
/helpers
/config
/middleware
/routes
