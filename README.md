# Learning Node
This is just a mocha setup that watches and runs any tests found inside the test directory (`/tests`). 

By default, all tests require a `.js` extension. 

## Running tests
```bash
# es6 (transpiled by babel)
npm test
```

## Expectation setup
All the expectations are handled by `chai.js`. The setup is located in `setup-globals.js`.
