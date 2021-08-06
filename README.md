# Webpack with Chrome Extension V3

## Installation

In the package root directory, run the `npm init` command.

```bash
npm init
```

### Install NPM Package

#### **Webpack**

* `Webpack` is a module bundler.

* Install [Webpack](https://www.npmjs.com/package/webpack) with npm:

  ```bash
  npm install --save-dev webpack
  npm install --save-dev webpack-cli
  npm install --save-dev webpack-dev-server
  npm install --save-dev clean-webpack-plugin
  npm install --save-dev copy-webpack-plugin
  npm install --save-dev html-webpack-plugin
  ```

* Read Webpack [Guides](https://webpack.js.org/guides/development/)

#### Asset Management

```bash
npm install --save-dev style-loader css-loader file-loader html-loader
npm install sass-loader sass webpack --save-dev
npm install babel-loader babel-minify --save-dev
npm i -D source-map-loader
```

#### Others

```node
npm install --save-dev fs-extra
```

#### Create/Edit Files in the Project

1. Edit `package.json`
  ```json
  "scripts": {
    "start": "node utils/webserver.js",
    "watch": "webpack --watch",
    "watch:dev": "webpack --watch --mode development",
    "build": "webpack",
  },
  ```
2. Create `webpack.config.js`

#### Test/Run Webpack

```
npm run start
npm run watch
npm run watch:dev
npm run build
```