# IMPORTANT NOTE

This fork has been converted to ES5 of purposes of compiling the package with other vanilla JS packages. *DO NOT MAKE CONTRIBUTIONS TO THIS FORK DIRECTLY.*

Pulling any master changes directly into index.js will explode horribly.

# strict-uri-encode [![Build Status](https://travis-ci.org/kevva/strict-uri-encode.svg?branch=master)](https://travis-ci.org/kevva/strict-uri-encode)

> A stricter URI encode adhering to [RFC 3986](http://tools.ietf.org/html/rfc3986)


## Install

```
$ npm install strict-uri-encode
```


## Usage

```js
const strictUriEncode = require('strict-uri-encode');

strictUriEncode('unicorn!foobar');
//=> 'unicorn%21foobar'

strictUriEncode('unicorn*foobar');
//=> 'unicorn%2Afoobar'
```


## API

### strictUriEncode(string)

#### string

Type: `string` `number`

String to URI encode.


## License

MIT © [Kevin Mårtensson](https://github.com/kevva)
