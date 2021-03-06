#generator-hottowel

## 0.6.1 - Nodalous-Ate-Us

### Features
- Updated to recent Sinon version

### Bug Fixes
- Updated nodemon in the gulpfile to use --inspect or --debug based on the node version (using semver package)
- Missing comma fix

## 0.4.0 - Wuttus-tookusuous-solongous

### Features
- Updated to Angular 1.5 and all related dependencies
- Updated all bower dependencies to latest
- Updated to latest yeoman, thus also refactoring code for its breaking changes
  - These do not affect hot towel usage
- Updated to PhantomJS 2
- Changed all indentation logic to use 2 space indentations (updated jshint, jscs, and editorconfig)

### Bug Fixes
- Merged many PRs for minor enhancements to the drop down menu to work in responsive mode

## 0.2.9 - Correctorus Maximus Erronoeous

### Features
- None

### Bug Fixes

- Fixed jshintrc maxerr to 50

## 0.2.5 - Path Clarity

### Features
- Clarified paths in gulp.config.js for node_modules
- Added .idea to .gitignore

### Bug Fixes

- Fixed font awesome path to use bower folder

## 0.2.4 - Spatial Whiteness

### Features
none

### Bug Fixes

- Removed whitespace in HTML files causing extra spacing for injection
- Removed comma in JSON in gulp.config.js

## 0.2.3 - Sequential Bellaspectral

### Features

- fixed sorting for the specs

## 0.2.2 - Sequential Stubranium

### Features

- added support for stubbing data from http calls
- injected files are now sorted using gulp-order

### Bug Fixes

- none

## 0.2.1 - Inpsectuous Injectulous 404zation

### Features

- added changelog
- extracted function for setting up node options
- extracted function for run node-inspector
- added 404 page inside the angular app in the core module
- otherwise route goes to 404 template
- node server routes template calls while unknown pages go to index.html

### Bug Fixes

- fixed bug that prevented node-inspector from working
- fixed bug that prevented html injection in the index.html

## 0.2.0 - Karmagulpulous Unification

### Features

- abstracted more of `karma.conf.js` out to `gulp.config.js`
- added `gulp-bump` and a related task
- a ton of refactoring to make the `gulp.config.js` more readable
- added nodemon logging
- exporting gulp as a proper module
- refactored testing to be cleaner

### Bug Fixes

- fixed bug that prevented karma from completing properly

## 0.0.12 - Gulp Craziness

### Features

- gulpfile.js contains several new tasks and refinements which will be in v1's documentation
- gulp.config.json --> gulp.config.js

