# periodicjs.ext.passport [![Coverage Status](https://coveralls.io/repos/github/githubUserOrgName/periodicjs.ext.passport/badge.svg?branch=master)](https://coveralls.io/github/githubUserOrgName/periodicjs.ext.passport?branch=master) [![Build Status](https://travis-ci.org/githubUserOrgName/periodicjs.ext.passport.svg?branch=master)](https://travis-ci.org/githubUserOrgName/periodicjs.ext.passport)

  A simple extension.

  [API Documentation](https://github.com/githubUserOrgName/periodicjs.ext.passport/blob/master/doc/api.md)

  ## Usage

  ### CLI TASK

  You can preform a task via CLI
  ```
  $ cd path/to/application/root
  ### Using the CLI
  $ periodicjs ext periodicjs.ext.passport hello  
  ### Calling Manually
  $ node index.js --cli --command --ext --name=periodicjs.ext.passport --task=hello 
  ```

  ## Configuration

  You can configure periodicjs.ext.passport

  ### Default Configuration
  ```javascript
  {
    settings: {
      defaults: true,
    },
    databases: {
    },
  };
  ```


  ## Installation

  ### Installing the Extension

  Install like any other extension, run `npm run install periodicjs.ext.passport` from your periodic application root directory and then run `periodicjs addExtension periodicjs.ext.passport`.
  ```
  $ cd path/to/application/root
  $ npm run install periodicjs.ext.passport
  $ periodicjs addExtension periodicjs.ext.passport
  ```
  ### Uninstalling the Extension

  Run `npm run uninstall periodicjs.ext.passport` from your periodic application root directory and then run `periodicjs removeExtension periodicjs.ext.passport`.
  ```
  $ cd path/to/application/root
  $ npm run uninstall periodicjs.ext.passport
  $ periodicjs removeExtension periodicjs.ext.passport
  ```


  ## Testing
  *Make sure you have grunt installed*
  ```
  $ npm install -g grunt-cli
  ```

  Then run grunt test or npm test
  ```
  $ grunt test && grunt coveralls #or locally $ npm test
  ```
  For generating documentation
  ```
  $ grunt doc
  $ jsdoc2md commands/**/*.js config/**/*.js controllers/**/*.js  transforms/**/*.js utilities/**/*.js index.js > doc/api.md
  ```
  ##Notes
  * Check out https://github.com/typesettin/periodicjs for the full Periodic Documentation