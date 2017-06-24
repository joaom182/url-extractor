# string-url-extractor
Lightweight JavaScript library for extract URLs from strings

### Usage
```javascript
const stringUrlExtractor = require('string-url-extractor');

let urls = stringUrlExtractor('Let`s extract some urls from this string, like http://some-url.com, https://some-url.com/path, some-url.io, www.some-url.com, ftp://some.ftp.com');

console.log(urls);
// Output
// ['http://some-url.com', 'https://some-url.com/path', 'some-url.io', 'www.some-url.com', 'ftp://some.ftp.com'];
```
