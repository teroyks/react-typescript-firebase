# Typescript & React Test

Simple React app, using Typescript, to be hosted on Firebase

## Installation

    npm init
    npm install react react-dom
    npm install --dev parcel-bundler @types/react @types/react-dom
    mkdir src

Create initial files:

- `App.tsx`
- `index.tsx`
- `index.html`

Add start script to `package.json`.

Run local dev server:

    npm start

## Deploy to Firebase

Create a project in Firebase, then configure deployment:

    firebase login
    firebase init
    firebase deploy

Init options:

- CLI features: hosting
- default project: select project
- public directory: `dist`
- do not overwrite `dist/index.html`

If you don't see your Firebase project at init:

Choose the _don't setup a default project_ option, then select project later with:

    firebase use --add
