# object from pairs

Create an object from an array of pairs

**Author:** [@brodybits (Christopher J. Brody)](https://github.com/brodybits)

**License:** CC0 OR UNLICENSE OR ISC OR Apache-2.0 OR CC-BY-SA-3.0 OR CC-BY-SA-4.0

## Sample

```js
const objectFromPairs = require('object-from-pairs')

console.log(objectFromPairs([
  [ 'first' + 'Key',        'first value' ],
  [ 'second' + '-' + 'key', 'second value' ],
]))
```

outputs the following:

```js
{ firstKey: 'first value', 'second-key': 'second value' }
```

(see [quick-demo.js](./quick-demo.js))

## TODO

- deeper testing
- proper API documentation
- use eslint-config-standard@12 when available (<https://github.com/standard/eslint-config-standard/issues/123>)
- follow (semi)standard more closely
- pre-es6 support
- test on browser
- test on AppVeyor & Travis CI
- SauceLabs?
- commit `package-lock.json` (??)

## See also

- <https://npm.im/object-from-entries>
- <https://lodash.com/docs/4.17.10#fromPairs>
- <https://github.com/lodash/lodash/issues/2718>
- <https://github.com/lodash/lodash/issues/1261>
- <https://stackoverflow.com/questions/20059995/how-to-create-an-object-from-an-array-of-key-value-pairs>
