> https://github.com/webmodules/blob was abandoned. This repo contains the latest versions published to NPM.

# Blob

A cross-browser `Blob` that falls back to `BlobBuilder` when appropriate.
If neither is available, it exports `undefined`.

## Installation

``` bash
$ npm install blob
```

## Example

``` js
var Blob = require('blob');
var b = new Blob(['hi', 'constructing', 'a', 'blob']);
```

## License

MIT
