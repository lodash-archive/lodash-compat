# lodash-compat v3.4.0

The [compatibility build](https://github.com/lodash/lodash/wiki/Build-Differences) of [lodash](https://lodash.com/) exported as [AMD](https://github.com/amdjs/amdjs-api/wiki/AMD) modules.

Generated using [lodash-cli](https://www.npmjs.com/package/lodash-cli):
```bash
$ lodash modularize compat exports=amd -o ./
$ lodash compat exports=amd -d -o ./main.js
```

## Installation

Defining a build as `'lodash'`.

```js
require({
  'packages': [
    { 'name': 'lodash', 'location': 'path/to/lodash-compat' }
  ]
}, ['lodash/array/chunk'], function(chunk) {
  // use `chunk`
});
```
