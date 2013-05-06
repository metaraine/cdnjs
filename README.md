# cdnjs

[![build status](https://secure.travis-ci.org/phuu/cdnjs.png)](http://travis-ci.org/phuu/cdnjs)

A search and URL retrival tool for [cdnjs](//cdnjs.com).

## Install

Install `cdnjs` globally:

`npm install -g cdnjs`

### Search

To search cdnjs:

`cdnjs search require`

```
require-cs                    : //cdnjs.cloudflare.com/ajax/libs/require-cs/0.4.2/cs.js
require-domReady              : //cdnjs.cloudflare.com/ajax/libs/require-domReady/2.0.1/domReady.js
require-i18n                  : //cdnjs.cloudflare.com/ajax/libs/require-i18n/2.0.1/i18n.js
require-jquery                : //cdnjs.cloudflare.com/ajax/libs/require-jquery/0.25.0/require-jquery.min.js
require-text                  : //cdnjs.cloudflare.com/ajax/libs/require-text/2.0.5/text.js
require.js                    : //cdnjs.cloudflare.com/ajax/libs/require.js/2.1.5/require.min.js
```

### URL

To get a url for a library:

`cdnjs url jquery`

```
jquery                        : //cdnjs.cloudflare.com/ajax/libs/jquery/1.9.1/jquery.min.js
```

### Default

With only one argument passed, `cdnjs` assumes you want to search.

`cdnjs angular`

```
Unknown method, assuming search.
angular-strap                 : //cdnjs.cloudflare.com/ajax/libs/angular-strap/0.7.1/angular-strap.min.js
angular-ui-bootstrap          : //cdnjs.cloudflare.com/ajax/libs/angular-ui-bootstrap/0.2.0/ui-bootstrap-tpls.min.js
angular-ui                    : //cdnjs.cloudflare.com/ajax/libs/angular-ui/0.4.0/angular-ui.min.js
angular.js                    : //cdnjs.cloudflare.com/ajax/libs/angular.js/1.1.1/angular.min.js
```

## License

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
