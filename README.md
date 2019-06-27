# gulptest-portfolio2
### Gulp Dependencies used:

1) gulp = Use Gulp 
2) gulp-sourcemaps = source map the orignal css code from the minified css file
3) gulp-postcss = CSS parser and runs autoprefixer and cssnano
4) autoprefixer = Adds vendor prefixes on css file
5) cssnano = Minifies the the css file
6) gulp-concat = Adds all JS files into one file
7) gulp-minify = Minifies JS file 
8) gulp-replace = Replace strings on files (cachebusting)

### Installation:

```
npm install --save-dev gulp gulp-sourcemaps gulp-postcss autoprefixer cssnano gulp-concat gulp-minify gulp-replace
```

### Prerequisites

* Change the links and script source to the dist/ folder.
* Add **"?cb=123"** to both the script and stylesheet to enable cache busting.

```
<link rel="stylesheet" type="text/css" href="dist/style.css?cb=123">
...
<script src="dist/all-min.js?cb=123" type="text/javascript"></script>
```
