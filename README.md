Bitcore Vidulum Library
=======

A pure and powerful JavaScript Vidulum library.

## Principles

Vidulum is a powerful new peer-to-peer platform for the next generation of financial technology. The decentralized nature of the Vidulum network allows for highly resilient Vidulum infrastructure, and the developer community needs reliable, open-source tools to implement Vidulum apps and services.

## Get Started

```
git clone https://github.com/Corey-Code/bitcore-lib-vidulum.git
cd bitcore-lib-vidulum
npm install
```


## Documentation

The complete docs are hosted here: [bitcore documentation](http://bitcore.io/guide/). There's also a [bitcore API reference](http://bitcore.io/api/) available generated from the JSDocs of the project, where you'll find low-level details on each bitcore utility.

- [Read the Developer Guide](http://bitcore.io/guide/)
- [Read the API Reference](http://bitcore.io/api/)

To get community assistance and ask for help with implementation questions, please use our [community forums](https://forum.bitcore.io/).

## Examples

* [Generate a random address](https://github.com/Corey-Code/bitcore-lib-vidulum/blob/master/docs/examples.md#generate-a-random-address)
* [Generate a address from a SHA256 hash](https://github.com/Corey-Code/bitcore-lib-vidulum/blob/master/docs/examples.md#generate-a-address-from-a-sha256-hash)
* [Import an address via WIF](https://github.com/Corey-Code/bitcore-lib-vidulum/blob/master/docs/examples.md#import-an-address-via-wif)
* [Create a Transaction](https://github.com/Corey-Code/bitcore-lib-vidulum/blob/master/docs/examples.md#create-a-transaction)
* [Sign a Vidulum message](https://github.com/Corey-Code/bitcore-lib-vidulum/blob/master/docs/examples.md#sign-a-bitcoin-message)
* [Verify a Vidulum message](https://github.com/Corey-Code/bitcore-lib-vidulum/blob/master/docs/examples.md#verify-a-bitcoin-message)
* [Create an OP RETURN transaction](https://github.com/Corey-Code/bitcore-lib-vidulum/blob/master/docs/examples.md#create-an-op-return-transaction)
* [Create a 2-of-3 multisig P2SH address](https://github.com/Corey-Code/bitcore-lib-vidulum/blob/master/docs/examples.md#create-a-2-of-3-multisig-p2sh-address)
* [Spend from a 2-of-2 multisig P2SH address](https://github.com/Corey-Code/bitcore-lib-vidulum/blob/master/docs/examples.md#spend-from-a-2-of-2-multisig-p2sh-address)


## Security

We're using Bitcore in production, as are [many others](http://bitcore.io#projects), but please use common sense when doing anything related to finances! We take no responsibility for your implementation decisions.

If you find a security issue, please email security@bitpay.com.

## Building the Browser Bundle

To build a bitcore-lib full bundle for the browser:

```sh
gulp browser
```

This will generate files named `bitcore-lib-vidulum.js` and `bitcore-lib-vidulum.min.js`.

You can also use our pre-generated files

## Development & Tests

```sh
git clone https://github.com/Corey-Code/bitcore-lib-vidulum
cd bitcore-lib-vidulum
npm install
```

Run all the tests:

```sh
gulp test
```

You can also run just the Node.js tests with `gulp test:node`, just the browser tests with `gulp test:browser`
or create a test coverage report (you can open `coverage/lcov-report/index.html` to visualize it) with `gulp coverage`.

## License

Code released under [the MIT license](https://github.com/Corey-Code/bitcore-lib-vidulum/blob/master/LICENSE).

Copyright 2013-2015 BitPay, Inc. Bitcore is a trademark maintained by BitPay, Inc.
