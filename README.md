# lodash-compat v3.10.2

The compatibility build of [lodash](https://lodash.com/) exported as [AMD](https://github.com/amdjs/amdjs-api/wiki/AMD) modules.

## Discontinued

This package has been discontinued. No further development is expected.

## Installation

Using an AMD loader:
```js
require({
  'packages': [
    { 'name': 'lodash', 'location': 'path/to/lodash-compat' }
  ]
}, ['lodash/array/chunk'], function(chunk) {
  // use `chunk`
});
```
