# smartswap-eslint-config

Smartswap ESLint config to enforce coding standards and best practices.

- TypeScript and Jest support
- Seamless Prettier integration
- Separate environments for Node.js and React

## Installation

```bash
yarn add --dev eslint smartswap-eslint-config
```

## Usage

> Make sure to include `require('smartswap-eslint-config/load')` at the top of your ESLint config. This loads a `@rushstack/eslint-patch/modern-module-resolution` patch so that ESLint loads any plugins installed by this package. 

```js
require('smartswap-eslint-config/load')

module.exports = {
  extends: 'smartswap-eslint-config/node'
}
```

or:

```js
require('smartswap-eslint-config/load')

module.exports = {
  extends: 'smartswap-eslint-config/react'
}
```

