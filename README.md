# React Template

Baseline React application boilerplate - clone, update package.json, and good to go.

## Usage

Started as a baseline from [Youtube clip](https://www.youtube.com/watch?v=mB1TKceLzh0&ab_channel=PedroTech).

Requirements
* node
* 

## Process

### 1. Set up baseline `package.json` file:
```
npm init -y
```
* `npm init` - creates baseline `package.json` file
  * `-y` argument - responds yes to all questions

### 2. Install `webpack` dependencies (development only)

* `npm install --save-dev webpack`
  * [webpack](https://www.npmjs.com/package/webpack) - Webpack is a module bundler. Its main purpose is to bundle JavaScript files for usage in a browser, yet it is also capable of transforming, bundling, or packaging just about any resource or asset.
* `npm install --save-dev webpack-cli`
  * [webpack-cli](https://www.npmjs.com/package/webpack-cli)

### 3. Install `react` dependencies
* `npm install react`
* `npm install react-dom`

### 4. Install `babel` dependencies (development only)
* `npm install --save-dev babel-loader`
  * [babel-loader](https://webpack.js.org/loaders/babel-loader) - This package allows transpiling JavaScript files using [Babel](https://github.com/babel/babel) and [webpack](https://github.com/webpack/webpack).
* `npm install --save-dev @babel/preset-env`
  * [@babel/preset-env](https://babeljs.io/docs/babel-preset-env) - a smart preset that allows you to use the latest JavaScript without needing to micromanage which syntax transforms (and optionally, browser polyfills) are needed by your target environment(s). This both makes your life easier and JavaScript bundles smaller!
* @babel/core
* @babel/preset-react
* babel-eslint
* @babel/runtime

