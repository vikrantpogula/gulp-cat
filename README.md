# gulp-cat [![Build Status](https://travis-ci.org/ben-eb/gulp-cat.svg?branch=master)](https://travis-ci.org/ben-eb/gulp-cat) [![NPM version](https://badge.fury.io/js/gulp-cat.svg)](http://badge.fury.io/js/gulp-cat) [![Dependency Status](https://gemnasium.com/ben-eb/gulp-cat.svg)](https://gemnasium.com/ben-eb/gulp-cat)

> Echo file(s) to the console.

Echo the contents of files to the console. Great for ASCII art, banners and important documentation. Inspired by https://npmjs.org/package/grunt-cat

## Installation

Install via [npm](https://npmjs.org/package/gulp-cat):

```
npm install gulp-cat --save-dev
```

## Example

```js
var gulp = require('gulp');
var cat  = require('gulp-cat');

gulp.task('default', function() {
    return gulp.src('./README.md')
        .pipe(cat());
});
```

## Contributing

Pull requests are welcome. If you add functionality, then please add unit tests to cover it.

## License

MIT © Ben Briggs
