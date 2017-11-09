# eslint-config-8select-node

> This is a proposal for a node ESLint config based on [Standard](https://github.com/feross/standard) for JavaScript code at 8select.


## Installation

```
npm i -D eslint @8select/eslint-config-8select-node
```


## Usage

Once you installed `@8select/eslint-config-8select-node`, you can use it by specifying `8select-node` in the [`extends`](http://eslint.org/docs/user-guide/configuring#extending-configuration-files) section of your [ESLint configuration](http://eslint.org/docs/user-guide/configuring).

```js
{
  "extends": "8select-node",
  "rules": {
    // Additional, per-project rules...
  }
}
```


## License

MIT © 8select Software GmbH
