# react-redux-boiler

**Super-simple react-redux boilerplate with enough useful goodies to develop [and build!] your cool app™, and nothing more ☺️**

## Installed packages

- 💪 Leverage [webpack 2.0](https://webpack.github.io) for easy development and builds

- ⌚️ Build intelligent components in no time with [react-bootstrap](https://react-bootstrap.github.io)

- 🚦 Navigate to routes via actions and sync them to your store with [redux-little-router](https://github.com/FormidableLabs/redux-little-router)

- 👯 Get sassy with your css with [sass-loader](https://github.com/webpack-contrib/sass-loader)

- 👨 Show your grandpa on internet explorer your app with [Autoprefixer](https://github.com/postcss/autoprefixer)

- 🤖 Write next-gen javascript (ES6+) and stay cross-browser compatible with [Babel](https://babeljs.io/)

- 🚿 Write clean and consistent next-gen javascript with [ESLint](http://eslint.org/)

- 🏗 Build production-ready cache-busting assets with [webpack-html-plugin](https://github.com/jantimon/html-webpack-plugin)

- 😻 Efficient and *cooler* dependency management with [Yarn](https://yarnpkg.com/) *[Note: you can still use npm if you prefer]*

## Also recommended

 - 🔥 [Firebase](firebase.google.com) for hyper-simple app deployment hosting, authentication, & backend

## Feedback

Think this boilerplate could be better? Open an issue, make a pull request, or just holla on: iam (at) rossdyson.com 

## Usage

### Install dependencies
```sh
yarn install
```

### Test app on a development server
```sh
yarn run start
```
Dev app will be up on localhost:9999 and any changes to files inside /src will automagically update the app ✨


### Build app
```sh
yarn run build:production
```
Builds a production-ready app in ./build


### Host built app (must have been built)
```sh
yarn run build:serve
```
The built production app will be hosted on localhost:8079

### Lint code
```sh
yarn run format
```
Cleans your codebase to follow the rules set in your eslintrc file. Useful for CI build tools.
