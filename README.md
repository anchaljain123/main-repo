[![SubmoduleSync Logo](https://i.imgur.com/YHmEmrs.png?1)]()

  Fast, minimalist  `gitsubmodule-sync` for [node](http://nodejs.org).

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
$ npm install syncsubmodule
```

## Description :

  > It is a shell script which handles the interaction between project and other gitsubmodules while committing on git , very easily . It will allow us to
  update all submodules with their latest updates and checkout to branch of project so that they are in sync .
  It irradicates the need for manually moving into submodule directory and stashing/committing their changes and then switching to branch where
  project is currently on . It also checks your linting which you will be specifying for your project . If script runs
  successfully then you can continue with push command .


## Instructions to Follow :

  * npm install syncsubmodule
  * Simply edit in your project's package.json, such as:

    `package.json`

  ```
    ...
    "scripts": {
        "updateSubmodule": "sh ./node_modules/syncsubmodule/update-submodule.sh",
        "lint": "eslint .",
        "precommit-msg":"echo 'Pre-commit checks... !!'"
    },
    "precommit":["precommit-msg","updateSubmodule"]
    ...
  ```

  * Start coding

## Features

  * Focus on high performance
  * Easy working with git
  * Executable for pushing applications quickly
  * Checks Eslint

## Philosophy

  The syncsubmodule philosophy is to provide small, robust tooling for synchronization between all submodules
  with main repository, making it a great solution for single page applications, web sites.

## Example

  To try the example, clone the repository and install the dependencies:

```bash
$ git clone git@github.com:anchaljain123/syncsubmodule.git
$ Under this repository,
    git submodule add git@github.com:anchaljain123/submodule-repo.git
$ start coding ,committing & pushing on git
```

  Then run example :

```bash
$ npm start
```
Install dependencies:

```bash
$ npm install
```

**ThankYou !!**

[npm-image]: https://img.shields.io/npm/v/express.svg
[travis-image]: https://img.shields.io/travis/expressjs/express/master.svg?label=linux
[appveyor-image]: https://img.shields.io/appveyor/ci/dougwilson/express/master.svg?label=windows


