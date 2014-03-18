Heroku Buildpack for Node and Gulp
==================================

Adds [gulp](https://github.com/gulpjs/gulp) support to the [standard Node buildpack](https://github.com/heroku/heroku-buildpack-nodejs).



## Usage

Add a gulp task named `heroku:production` and it will be run automatically when you deploy.

```bash
$ heroku config:set BUILDPACK_URL=https://www.github.com/jameswyse/heroku-buildpack-node-gulp.git 
$ heroku labs:enable user-env-compile
$ heroku config:set NODE_ENV=production
```

## Credits

Based on:
- [heroku-buildpack-nodejs-gulp](https://github.com/timdp/heroku-buildpack-nodejs-gulp)
- [heroku-buildpack-nodejs](https://github.com/heroku/heroku-buildpack-nodejs)
- [heroku-buildpack-nodejs-grunt](https://github.com/mbuchetics/heroku-buildpack-nodejs-grunt)

## License

Copyright (C) 2012-2014 Heroku, Inc.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
