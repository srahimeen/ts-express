

# Express + TypeScript Boilerplate
A lightweight process to get an Express + TypeScript project set up and running.

## Create node project

    npm init

## Install TypeScript and Express

    npm i -D typescript
    npm i express
    npm i -D @types/express @types/node

## Create tsconfig.json

    npx tsc --init

## Install ts-node
Alternative to nodemon for TypeScript.

    npm i -D ts-node

## Add tests

    npm i -D jest ts-jest @types/jest
    npm i -D supertest @types/supertest

## Add jest config
Required for running supertest and jest tests in TypeScript.

    "jest": {
        "transform": {
        "^.+\\.(ts|tsx)$": "ts-jest"
        }
    }

## Add jest script

    "test": "jest"

## Add run script

    "start": "ts-node index.ts"
    
## Create index.ts file

    // entry point for express app

