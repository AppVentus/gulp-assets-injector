# gulp-assets-injector [![Build Status](https://travis-ci.org/loicgoyet/gulp-assets-injector.svg?branch=master)](https://travis-ci.org/loicgoyet/gulp-assets-injector)

> My stylish gulp plugin


## Install

```
$ npm install --save-dev gulp-assets-injector
```


## Usage

```js
var gulp = require('gulp');
var assetsInjector = require('gulp-assets-injector');

gulp.task('default', function () {
	return gulp.src('src/file.ext')
		.pipe(assetsInjector())
		.pipe(gulp.dest('dist'));
});
```


## API

### assetsInjector(options)

#### options

##### foo

Type: `boolean`  
Default: `false`

Lorem ipsum.


## License

MIT © [Loïc Goyet](https://github.com/loicgoyet)
