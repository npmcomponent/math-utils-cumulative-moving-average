*This repository is a mirror of the [component](http://component.io) module [math-utils/cumulative-moving-average](http://github.com/math-utils/cumulative-moving-average). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/math-utils-cumulative-moving-average`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# Cumulative Moving Average [![Build Status](https://travis-ci.org/math-utils/cumulative-moving-average.png)](https://travis-ci.org/math-utils/cumulative-moving-average)

## API

```js
var cma = require('cumulative-moving-average')

var avg = cma()

avg.push(1)
console.log(avg.value) // 1
console.log(avg.length) // 1

avg.push(3)
console.log(avg.value) // 2
console.log(avg.length) // 2
```

## License

The MIT License (MIT)

Copyright (c) 2013 Jonathan Ong me@jongleberry.com

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.