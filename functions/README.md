# Cloud Functions

## Initialization

    firebase init
    cd functions
    npm install firebase-admin@latest firebase-functions@latest

Init options:

- typescript
- use TSLint
- install dependencies

## Local Server

    npm run serve

Note: does not rebuild automatically

Hot rebuild:

    tsc --watch &
    firebase serve

Runs updated function on browser reload.

## Deployment

    npm run deploy
