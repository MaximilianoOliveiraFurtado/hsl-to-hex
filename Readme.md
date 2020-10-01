# hsl-to-hex
Convert HSL colors to RGB colors in hex format.

## Install
```sh
npm install --save @maximiliano.oliveira.furtado/hsl-to-hex
```

## API
```
require('hsl-to-hex') = > Function
hsl(hue, saturation, luminosity)` => String
```

## Example
```js
var toRgb = require('hsl-to-hex')
var hue = 133
var saturation = 40
var luminosity = 60
var hex = hsl(hue, satturation, luminosity)
console.log(hex) // #70c282
```
## License

ISC