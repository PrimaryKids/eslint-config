[![lerna](https://img.shields.io/badge/maintained%20with-lerna-cc00ff.svg)](https://lerna.js.org/)

# @primarykids/eslint-config

A shared set of ESLint configuration files.

## Installation

These packages are published to Github's package registry. A personal access token (PAT) is needed in order to install them into a project.
See [Authenticating with a personal access token](https://docs.github.com/en/packages/working-with-a-github-packages-registry/working-with-the-npm-registry#authenticating-with-a-personal-access-token).

You'll most likely want to use either `@primarykids/eslint-config-typescript` or `@primarykids/eslint-config-react-ts` in your project.

### Install with yarn

```bash
yarn add @primarykids/eslint-config-typescript -D
```

or

```bash
yarn add @primarykids/eslint-config-react-ts -D
```

### Configure `.eslintrc.js`

```js
module.exports = {
  extends: [
    '@primarykids/eslint-config-typescript', // or '@primarykids/eslint-config-react-ts'
  ],
}
```

## Publishing

To publish new versions to the Github Package Registry using `lerna`, run

```bash
yarn publish
```
