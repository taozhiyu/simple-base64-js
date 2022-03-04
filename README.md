# simple-base64-js
a simple base64 js class, compatible with Unicode characters


```js
（copy base64.js context here）
var Base64={.....}
console.group('Test Base64: ');
var b64 = Base64.encode('Hello, oschina！又是一年春来到~');
console.log(b64);
console.log(Base64.decode(b64));
console.groupEnd();
```
