# lodash-compat v3.10.1

The [compatibility build](https://github.com/lodash/lodash/wiki/Build-Differences) of [lodash](https://lodash.com/) exported as [AMD](https://github.com/amdjs/amdjs-api/wiki/AMD) modules.

Generated using [lodash-cli](https://www.npmjs.com/package/lodash-cli):
```bash
$ lodash modularize compat exports=amd -o ./
$ lodash compat exports=amd -d -o ./main.js
```

## Installation

Using bower or volo:

```bash
$ bower i lodash-compat#3.10.1-amd
$ volo add lodash-compat/3.10.1-amd
```

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
