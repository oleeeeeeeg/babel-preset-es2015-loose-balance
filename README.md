# babel-preset-es2015-loose-balance

> Babel preset es2015 with some optimisations.

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "presets": ["es2015"]
}
```

### Via CLI

```sh
$ babel script.js --presets es2015 
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  presets: ["es2015"]
});
```
