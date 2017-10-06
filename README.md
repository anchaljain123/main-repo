[![SubmoduleSync Logo](https://i.imgur.com/YHmEmrs.png?1)]()

  Fast, minimalist gitsubmodule-sync for [node](http://nodejs.org).

  ![NPM Version][npm-image]
  ![Linux Build][travis-image]
  ![Windows Build][appveyor-image]

## Installation

This is a [Node.js](https://nodejs.org/en/) module available through the
[npm registry](https://www.npmjs.com/).

Before installing, [download and install Node.js](https://nodejs.org/en/download/).
Node.js 0.10 or higher is required.

Installation is done using the
[`npm install` command](https://docs.npmjs.com/getting-started/installing-npm-packages-locally):

```bash
$ npm install submoduleSync
```

## Instrunctions to Follow :

  * npm install submoduleSync
  * Refer 'package.json' of ./node_modules/submoduleSync/package.json & Edit your packgae.json
  * Copy update-submodule.sh into your project at root level

## Features

  * Module-submodule SyncUp
  * Focus on high performance
  * Easy working with git
  * Executable for pushing applications quickly
  * Checks Eslint & in success will run successfully otherwise will break

## Philosophy

  The submoduleSync philosophy is to provide small, robust tooling for synchronization between all submodules
  with main repository, making it a great solution for single page applications, web sites.

  submoduleSync does not force you to use any specific ORM or template engine.
  you can quickly craft your perfect sync module.

## Examples

  To view the example, clone the mainrepo and install the dependencies:

```bash
$ git clone git@github.com:anchaljain123/main-repo.git
$ under this repo , git submodule add  git@github.com:anchaljain123/submodule-repo.git
$ npm install
```

  Then run example :

```bash
$ npm start
```
Install dependencies:

```bash
$ npm install
```

[npm-image]: https://img.shields.io/npm/v/express.svg
[travis-image]: https://img.shields.io/travis/expressjs/express/master.svg?label=linux
[appveyor-image]: https://img.shields.io/appveyor/ci/dougwilson/express/master.svg?label=windows


