# RedTurtle - eslint-config-react

[![Build Status](https://travis-ci.org/RedTurtle/eslint-config-react.svg?branch=master)](https://travis-ci.org/RedTurtle/eslint-config-react)

This package provides the [RedTurtle default eslint-config](https://github.com/RedTurtle/eslint-config), with added react rules.

## Installation and usage

Install with yarn or npm:

```shell
# Yarn
$ yarn add --dev @redturtle/eslint-config-react

# Npm
$ npm install --save-dev @redturtle/eslint-config-react
```

If you don't have those already, install peer dependencies:

```shell
# Yarn
$ yarn add --dev babel-eslint eslint eslint-config-prettier eslint-plugin-import eslint-plugin-prettier prettier

# Npm
$ npm install --save-dev babel-eslint eslint eslint-config-prettier eslint-plugin-import eslint-plugin-prettier prettier
```

Extend this config in your `.eslintrc` file:

```json
{
  "extends": "@redturtle/react"
}
```
