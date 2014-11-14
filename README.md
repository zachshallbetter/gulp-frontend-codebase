Gulp frontend codebase
======================

After trying different front-end configurations in the past few months (grunt or gulp, haml or slim, ES6 modules or AMD modules, etc) I have finally found one that I'm pretty comfortable with (at least for a while). This codebase is using:

- [Gulp](http://gulpjs.com/)
- [Slim](http://slim-lang.com/)
- [SASS](http://sass-lang.com/)
- [Autoprefixer](https://github.com/postcss/autoprefixer-core)
- [Traceur](https://github.com/google/traceur-compiler) for IE6 transpile. (wrapper for command line traceur) 

### Next steps
Try and incorporate performance tools (like [uncss](https://github.com/ben-eb/gulp-uncss), [critical-path](https://github.com/addyosmani/critical-path-css-demo)) and testing tools.