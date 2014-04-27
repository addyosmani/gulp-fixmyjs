# gulp-fixmyjs
[![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url]  [![Coverage Status][coveralls-image]][coveralls-url] [![Dependency Status][depstat-image]][depstat-url]

> fixmyjs plugin for [gulp](https://github.com/wearefractal/gulp)


## Project status
This project is a work-in-progress, and could be buggy.

## Usage

First, install `gulp-fixmyjs` as a development dependency:

```shell
npm install --save-dev gulp-fixmyjs
```

Then, add it to your `gulpfile.js`:

```javascript
var fixmyjs = require("gulp-fixmyjs");

gulp.src("./src/*.ext")
	.pipe(fixmyjs({
		msg: "Hello Gulp!"
	}))
	.pipe(gulp.dest("./dist"));
```

## API

### fixmyjs(options)

#### options.msg
Type: `String`  
Default: `Hello World`

The message you wish to attach to file.


## License

[MIT License](http://en.wikipedia.org/wiki/MIT_License)

[npm-url]: https://npmjs.org/package/gulp-fixmyjs
[npm-image]: https://badge.fury.io/js/gulp-fixmyjs.png

[travis-url]: http://travis-ci.org/kcherkashin/gulp-fixmyjs
[travis-image]: https://secure.travis-ci.org/kcherkashin/gulp-fixmyjs.png?branch=master

[coveralls-url]: https://coveralls.io/r/kcherkashin/gulp-fixmyjs
[coveralls-image]: https://coveralls.io/repos/kcherkashin/gulp-fixmyjs/badge.png

[depstat-url]: https://david-dm.org/kcherkashin/gulp-fixmyjs
[depstat-image]: https://david-dm.org/kcherkashin/gulp-fixmyjs.png
