# Introduction

This pages describes how to write and run tests in POGS.

# Backend tests

Backend tests can be run from maven or the IDE. Just run `mvn test` in the repo root.

# Frontend tests

Frontend tests are run using Karma. You need to install karma:


## Running frontend tests

```
npm install -g karma
```

Then you can run the tests with `karma start` in the repo root.

## Writing frontend tests

You can test all files in the `src/main/resources/static/js/lib` directory. Just add a `*__tests.js` file with the tests, see `src/main/resources/static/js/lib/ot__tests.js` for reference.
