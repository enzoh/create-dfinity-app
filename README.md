# Create Dfinity App

The easiest way to use Create React App with Dfinity

### Requirements
Make sure you have the latest Dfinity SDK installed before starting it
https://sdk.dfinity.org/docs/download.html

### Create an App
Pick your preferred package manager
```sh
npm init react-app my-app --template dfn
yarn create react-app my-app --template dfn
```

### Start the backend 
```sh
cd my-app

dfx start --background
dfx canister create --all
dfx build
dfx canister install test
```

### Now use CRA as usually
```
npm start
yarn start
```
