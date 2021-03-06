# npm Front-End Workflow [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

>Useful resources for npm based front-end development workflows and using npm as a build tool.

## Articles

- [Introduction to NPM Scripts](https://medium.freecodecamp.org/introduction-to-npm-scripts-1dbb2ae01633) Author: Mohammed Ajmal Siddiqui
- [How to Use npm as a Build Tool](https://www.keithcirkel.co.uk/how-to-use-npm-as-a-build-tool/) Author: Keith Cirkel
- [npm based front-end workflow](https://morocco.js.org/tutorials/npm-based-front-end-workflow/) Author: Youssef Kababe
- [Utilising Node.js and npm for front-end development workflow](http://jsforallof.us/2015/02/12/utilising-node-and-npm-for-front-end-development-workflow/) Author: Ben Howdle
- [Why npm Scripts?](https://css-tricks.com/why-npm-scripts/) Author: Damon Bauer
- [Why I Left Gulp and Grunt for npm Scripts](https://medium.freecodecamp.com/why-i-left-gulp-and-grunt-for-npm-scripts-3d6853dd22b8#.sl4nc2cm7) Author: Cory House

## Live Server - Autoreload

- [Browsersync](https://www.browsersync.io) Browsers are automatically updated as you change HTML, CSS, images and other project files.
- [browser-refresh](https://github.com/patrick-steele-idem/browser-refresh) Node.js module to enable server restart and browser refresh in response to file modifications.
- [reload](https://github.com/jprichardson/reload) Refresh and reload your code in your browser when your code changes. No browser plugins required.
- [live-server](https://github.com/tapio/live-server) A simple development http server with live reload capability.
- [live-reload](https://github.com/Raynos/live-reload) A live reload server & client

## File Watcher

- [rerun-script](https://github.com/wilmoore/rerun-script) Invoke npm scripts upon file changes.
- [onchange](https://github.com/Qard/onchange) Use glob patterns to watch file sets and run a command when anything is added, changed or deleted.
- [watch](https://github.com/mikeal/watch)  Utilities for watching file trees.
- [npm-watch](https://github.com/M-Zuber/npm-watch) Run scripts from package.json when files change.

## Run Scripts in Paralell 

- [npm-run-all](https://github.com/mysticatea/npm-run-all) A CLI tool to run multiple npm-scripts in parallel or sequential.
- [better-npm-run](https://github.com/benoror/better-npm-run) Better NPM scripts runner
- [concurrently](https://github.com/kimmobrunfeldt/concurrently) Run multiple commands concurrently. Like npm run watch-js & npm run watch-less but better.

## Copy / Synchronize Files

- [cpx](https://github.com/mysticatea/cpx) A cli tool to watch and copy file globs. 
- [copyfiles](https://github.com/calvinmetcalf/copyfiles) Copy files on the command line 
- [cpy-cli](https://github.com/sindresorhus/cpy-cli) User-friendly by accepting globs and creating non-existant destination directories.
- [ncp](https://github.com/AvianFlu/ncp) Asynchronous recursive file & directory copying.
- [node-sync-files](https://github.com/byteclubfr/node-sync-files) Synchronize files or folders locally, with a watch option.

## CSS Processors

- [postcss-cli](https://github.com/postcss/postcss-cli) Postcss Command Line Iterface
- [stylus](https://github.com/stylus/stylus) Robust, expressive, and feature-rich CSS superset
- [node-sass](https://github.com/sass/node-sass) Node.js bindings to libsass
- [less.js](https://github.com/less/less.js) This is the JavaScript, official, stable version of Less.

## CSS Optimization

- [clean-CSS](https://github.com/jakubpawlowicz/clean-css) Fast and efficient CSS optimizer for node.js and the Web
- [Purgecss](https://github.com/FullHuman/purgecss) Purgecss removes unused selectors from your css, resulting in smaller css files.
- [PurifyCSS](https://github.com/purifycss/purifycss) A function that takes content (HTML/JS/PHP/etc) and CSS, and returns a file made up of only the selectors you use.
- [PurifyCSS Extended](https://github.com/HapLifeMan/purifycss-extended) Fork from the original purifycss
- [uncss](https://github.com/giakki/uncss) UnCSS is a tool that removes unused CSS from your stylesheets. It works across multiple files and supports Javascript-injected CSS.
- [dropcss](https://github.com/leeoniya/dropcss) A simple, thorough and fast unused-CSS cleaner

## Image Optimization

- [imagemin-cli](https://github.com/imagemin/imagemin-cli) Minify images seamlessly
- [imageoptim-cli]() Automates ImageOptim, ImageAlpha, and JPEGmini (commercial software) for Mac to make batch optimisation of images part of your automated build process.

## Cross-platform Utilities

Utilities to perform common command-line tasks without worrying about cross-platform compatibility.

- [rimraf](https://github.com/isaacs/rimraf) - Delete files or directories; like `rm -rf`.
- [del-cli](https://github.com/sindresorhus/del-cli) - Safer file and folder deletion.
- [mkdirp](https://github.com/substack/node-mkdirp) - Create a directory, creating parent directories if needed; like `mkdir -p`.
- [cpy-cli](https://github.com/sindresorhus/cpy-cli) - File/directory copying/renaming.
- [copyfiles](https://github.com/calvinmetcalf/copyfiles) - Copy a list of files into a directory.
- [sync-files](https://github.com/byteclubfr/node-sync-files) - `rsync`-like directory syncing with watch mode.
- [echo-cli](https://github.com/iamakulov/echo-cli) - Cross-platform `echo` with JS escape sequence support.
- [clear-cli](https://github.com/sindresorhus/clear-cli) - Clear the terminal.
- [cross-env](https://github.com/kentcdodds/cross-env) - Set environment variables for scripts, unix-style.
- [cross-os](https://github.com/milewski/cross-os) - Run platform-specific npm scripts.
- [ntee](https://github.com/stefanmaric/ntee) - Utility that reads from standard input and writes to standard output and files; like Unix `tee`.
- [catw](https://github.com/substack/catw) - Print a file to stdout, with optional watch mode; sorta like Unix `cat`.

## Styleguide Generators

- [postcss-style-guide](https://github.com/morishitter/postcss-style-guide) PostCSS plugin to generate a style guide automatically. CSS comments will be parsed through Markdown and displayed in a generated HTML document.
- [markdown-styleguide-generator](https://github.com/emiloberg/markdown-styleguide-generator) Will search all your (s)css files for comments and generate a single page html styleguide.
- [styledown](https://github.com/styledown/styledown) Markdown-based styleguide generator.
- [kss-node](https://github.com/kss-node/kss-node) To get you up and running quickly, a style guide generator is included that can be used from the command line. It parses stylesheets and spits out a set of static HTML files.

## Useful npm packages

- [grunty](https://github.com/bahmutov/grunty) Run any grunt plugin as NPM script without Gruntfile.js
- [nps](https://github.com/kentcdodds/nps) All the benefits of npm scripts without the cost of a bloated package.json and limits of json

## npm Resources and Tips

- [awesome npm](https://github.com/sindresorhus/awesome-npm) A curated list
- [awesome npm scripts](https://github.com/RyanZim/awesome-npm-scripts) Everything awesome for using npm as a build tool

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)
