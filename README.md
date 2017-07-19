# html-entities-decoder [![Version Number](https://img.shields.io/npm/v/html-entities-decoder.svg)](https://github.com/thx/html-entities-decoder/ "Version Number") [![License](https://img.shields.io/badge/license-MIT-orange.svg)](https://opensource.org/licenses/MIT "License") [![download](https://img.shields.io/npm/dm/html-entities-decoder.svg)](https://www.npmjs.com/package/html-entities-decoder)
decode all html entities

### Examples
> input : 1 &amp;copy; 2 &amp;#34;
> ouput : 1 © 2 "

### How to use
```js
let entitiesDecoder=require('html-entities-decoder');
let input ='1 &copy; 2 &#34;';
let output=entitiesDecoder(input);
```

### License
MIT