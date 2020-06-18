# node-js-getting-started
A barebones Node.js app using [Express 4](http://expressjs.com/).

This application supports the [Getting Started on Exorun with Node.js](https://exorun.io/docs/getting-started/nodejs) article - check it out.

## Running Locally

Make sure you have [Node.js](http://nodejs.org/) and the [Exorun CLI](https://exorun.io/docs/getting-started/installing-exorun) installed.

```sh
$ git clone https://github.com/exorunltd/node-js-getting-started.git # or clone your own fork
$ cd node-js-getting-started
$ npm install
$ npm start
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

## Deploying to Exorun

```
$ exorun create
$ git push exorun master
```