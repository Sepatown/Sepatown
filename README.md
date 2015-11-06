Sepatown
===========================

...

## Structure:

- app/
  - index.js
- public/
  - bundle.js
  - index.html
- package.json
- webpack.config.js

## Install:

Make sure you have webpack installed globably:

`$ npm i -g webpack`

Install npm dependencies:

`$ npm i`

Build your bundle:

`$ webpack`

You are now ready to go! Serve your index.html app via a server and you will see your Hello World react component rendered! 

## Webpack dev server

The [webpack-dev-server](https://webpack.github.io/docs/webpack-dev-server.html) is a little node.js Express server, which uses the webpack-dev-middleware to serve a webpack bundle. It also has a little runtime which is connected to the server via Socket.IO

Just run the server from the project root

`$ webpack-dev-server`

***


