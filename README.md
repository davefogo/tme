# tme

*Lightweight Node-based CLI testing framework that works as an alternative to Jest or Mocha.

## Installing

```
git clone https://github.com/davefogo/tme
cd tme/
npm install
```

## Getting started
See sample test file (`app.test.js`) in `samplewebproject/test` for an example.

```
cd appToBeTested/
create filename.test.js and write tests
tme filename.test.js
```

### Initial Configuration

To change excluded directories or files for the test collector go to `runner.js` and add to the `forbiddenDirs` array the folder or file names.


## Features

* Tests whole browser-based JS apps with very little setup. 
* 'watch mode' restarts the app each time a new change is made.
* Finds and runs all files that have a '*.test.js' in a given directory one by one.
* Excludes node_modules and can be customized as needed.
* Simulates the DOM using JsDom.

## Licensing

"The code in this project is licensed under MIT license."

