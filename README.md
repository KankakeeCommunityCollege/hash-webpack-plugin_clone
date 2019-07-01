# hash-webpack-plugin

> Clone of xpepermint's hash manifest file writer plugin for Webpack.

Original repository: https://github.com/xpepermint/hash-webpack-plugin

## Setup

```sh
npm install --save-dev hash-webpack-plugin
```

## Example

```js
...
const HashPlugin = require('hash-webpack-plugin');

module.exports = {
  ...
  plugins: [
    new HashPlugin({ path: './build', fileName: 'hash.txt' })
  ]
};
```
