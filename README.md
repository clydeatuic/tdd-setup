# tdd-setup
Test Driven Development using Node JS and webdriverio with Selenium

## [webdriverio API Documentation](http://webdriver.io/api.html)

## Requisites
* Node JS (Platform)
* Sublime Text (Text Editor)

## Terminal
1. Launch new terminal then we will label this as ```Terminal A``` and check the version of the following software
```console
$ node --version
$ npm --version
$ subl --version
```

1. Setup the activity directory
```console
$ cd desktop
$ mkdir tdd-setup-lastname && cd tdd-setup-lastname
```

1. Initialize node package.json and install ```webdriverio``` and ```selenium-standalone```
```console
$ npm init -y
$ npm install --save-dev webdriverio
$ npm install -g selenium-standalone
```

1. Launch new terminal then we will label this as ```Terminal B``` and install ```selenium-standalone```
```console
$ selenium-standalone install
```

1. Go back to ```Terminal A``` and create a folder ```test``` to hold all test scripts.
```console
$ mkdir test
$ subl .
```

1. Go to [webdriver.io](http://webdriver.io/) and copy the setup code provided in the documentation site.
```javascript

```

1. Update ```package.json```
```json
{
...
  "main": "index.js",
  "scripts": {
    "test": "node test/myfirsttest"
  },
  "keywords": [],
...
}
```

1. Execute the test
```console
$ node test/myfirsttest

or

$ npm test
```
