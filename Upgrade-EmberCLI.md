[Upgrade Ember CLI Version]

$ npm uninstall –g ember-cli
$ npm cache clean
$ bower cache clean
$ npm install –g ember-cli **$ npm install –g ember-cli@X.X.X**

[Update Existing Project]

$ rm –rf node_modules bower_components dist tmp
$ npm install ember-cli@X.X.X --save-dev **update package.json**
$ npm install **install all npm packages again**
$ bower install **install all bower packages again**
$ ember init
