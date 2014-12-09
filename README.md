
#openfin-launcher

A node module that downloads and launches the [OpenFin Runtime](http://openfin.co/)

Currently only Windows support.

### Install

```sh
$ npm install --save openfin-launcher
```

### Usage

```js
var openfinLauncher = require('openfin-launcher');

//for a non hosted app.json file
openfinLauncher.launchOpenFin({configPath:'file:/C:/helloWorld/app.json'});

//or a hosted app.json file
openfinLauncher.launchOpenFin({configPath:'http://localhost:5000/app.json'});
```
## License

MIT
