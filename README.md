# confirm-cli

A confirm interface in command line.

[![NPM version](https://badge.fury.io/js/confirm-cli.png)](http://badge.fury.io/js/confirm-cli)

---

## Install

```bash
$ npm install confirm-cli --save
```

## Usage

```js
confirm('Is this package awosome?',
  function() {
    console.log('Selected yes!');
  }, function() {
    console.log('Selected no!');
  });
```

![](https://t.alipayobjects.com/images/T1h0xeXihoXXXXXXXX.png)

Press `tab` (or `left` or `right` key) to switch current button, and press `enter` to confirm.

### Example

```bash
$ git clone git@github.com:afc163/confirm-cli.git
$ cd confirm-cli
& npm install
$ node example/basic.js
& node example/tabs.js
```

## License

The MIT License (MIT)