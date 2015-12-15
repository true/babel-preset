# babel-preset-true

> A babel preset for transforming your JavaScript for True.

## Install

```sh
$ npm install --save-dev babel-preset-true
```

## Usage

### `.babelrc`

```json
{
  "presets": ["true"]
}
```

### CLI

```sh
$ babel es6.js --presets true
```

### API

```js
require('babel-core').transform('foo', {
  presets: ['true']
});
```

## License

MIT © [True B.V.](https://true.nl)
