# object from pairs

Create an object from an array of pairs

**Author:** [@brodybits (Christopher J. Brody)](https://github.com/brodybits)

**License:** CC0 OR UNLICENSE OR ISC OR Apache-2.0 OR CC-BY-SA-3.0 OR CC-BY-SA-4.0

**Idea from:** <https://stackoverflow.com/questions/20059995/how-to-create-an-object-from-an-array-of-key-value-pairs>

## Sample

```js
const objectFromPairs = require('object-from-pairs')

console.log(objectFromPairs([
  [ 'first' + 'Key',        'first value' ],
  [ 'second' + '-' + 'key', 'second value' ],
]))
```

outputs the following:

```json
{ firstKey: 'first value', 'second-key': 'second value' }
```

(see [quick-demo.js](./quick-demo.js))

## TODO

- deeper testing
- proper API documentation
- eslint (standard or semistandard)
- test on browser
- test on AppVeyor & Travis CI
- SauceLabs?
- commit `package-lock.json` (??)
