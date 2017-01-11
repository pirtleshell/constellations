# constellations

> JSON list of astronomical constellations :star2:

The data is simply a JSON file, feel free to use in anywhere.

## Install

```sh
npm install --save constellations
```

## Structure

The data is a list of objects containing naming information about the constellations, arranged in alphabetical order.

```js
const constellations = require('constellations');

constellations.length
//=> 88

constellations[0]
//=> {
//   abbr: 'And',
//   name: 'Andromeda',
//   genitive: 'Andromedae',
//   en: 'Andromeda (mythological character)'
// }
```

The data is scraped from [this Wikipedia table](https://en.wikipedia.org/wiki/88_modern_constellations#List).

## License

This is by [Robert Pirtle](jhttps://pirtle.xyz). Its license is [MIT](http://choosealicense.com/licenses/mit/).
