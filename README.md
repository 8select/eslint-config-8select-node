# eslint-config-8select-lambda

> This is a proposal for a lambda ESLint config based on [Standard](https://github.com/feross/standard) for JavaScript code at 8select.


## Installation

```
# Install `eslint` from npm and `eslint-config-8select-lambda` from GitHub:
$ npm i eslint 8select/eslint-config-8select-lambda
```


## Usage

Once you installed `eslint-config-8select-lambda`, you can use it by specifying `8select-lambda` in the [`extends`](http://eslint.org/docs/user-guide/configuring#extending-configuration-files) section of your [ESLint configuration](http://eslint.org/docs/user-guide/configuring).

```js
{
  "extends": "8select-lambda",
  "rules": {
    // Additional, per-project rules...
  }
}
```


## License

MIT © 8select Software GmbH
