# Create Dfinity App

The easiest way to use Create React App with Dfinity

```sh
npx create-react-app my-app --template dfn
cd my-app

# First start the backend
dfx start --background
dfx canister create --all
dfx build
dfx canister install test

# Now use CRA as usually
npm start
```
