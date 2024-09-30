# [science-joy.com](https://www.science-joy.com/)

## Getting Started

### Deployment

This is currently deployed using [github actions](/.github/workflows/jekyll.yml). 
To run locally, setup jekyll and run ```jekyll serve```

### Compiling Styles

Following on the way Casper styles are compiled as [described here](https://github.com/tryghost/casper#development):

Jasper2 styles are compiled using Gulp/PostCSS to polyfill future CSS spec. You'll need Node and Gulp installed globally. After that, from the theme's root directory:

```bash
$ npm install
$ gulp
```

Now you can edit `/assets/css/` files, which will be compiled to `/assets/built/` automatically.

## Issues and Contributing

This install builds well with Ruby v2.6.3 and Jekyll v3.9.0. If you run into any problems
please log them on the [issue tracker](https://github.com/jekyllt/jasper2/issues).

Feel free pull-request your patches and fixes.

## Thanks

Many thanks to the Ghost team for all the design work. Also many thanks to all contributors,
that help keeping the project alive and updated :smile:


## Copyright & License

Same licence as the one provided by Ghost's team. See Casper's theme [license](GHOST.txt).

Copyright (C) 2015-2021 - Released under the MIT License.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
