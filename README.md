# ES6Webpack Scaffolding
Webpack and babel (transpile) scaffolding for JavaScript ES6 projects

### First steps
Dependencies installation:

```shell
npm install
```

### Build and watch the project
To start watching and compile the app run:

```shell
npm run webpack

```

### Configuration file
Modify the webpack configuration file `webpack.config.js` to change or add more options. [Official doc](https://webpack.js.org/concepts/)


#### Mode production/development
Bye default webpack is set to `development` change inside `webpack.config.js` the property mode from `development` to `production` this will also [minify the output](https://webpack.js.org/guides/tree-shaking/#minify-the-output) by default.

### link the app
link the the app inside the project:

```html
<script src="dist/app.bundle.js"></script>
```
Use the minified version using mode -> production



### NOTE: change mode to production before to go live
### Latest update 20 Jan 2019