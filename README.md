# babel-preset-es2015-only-transforms

> Babel preset for all es2015 plugins except `babel-plugin-check-es2015-constants`.

## Install

```sh
$ npm install --save-dev babel-preset-es2015-only-transforms
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "presets": ["es2015-only-transforms"]
}
```

### Via CLI

```sh
$ babel script.js --presets es2015-only-transforms 
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  presets: ["es2015-only-transforms"]
});
```
