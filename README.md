# Boxal

[![Coverage Status](https://coveralls.io/repos/github/boxal/boxal/badge.svg?branch=master)](https://coveralls.io/github/boxal/boxal?branch=master)
[![Build Status](https://travis-ci.org/boxal/boxal.svg?branch=master)](https://travis-ci.org/boxal/boxal)
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)
[![Stories in Ready](https://badge.waffle.io/boxal/boxal.png?label=ready&title=Ready)](https://waffle.io/boxal/boxal)
## npm scripts

### Dev
```bash
$ npm run dev
```

This runs a development mode server with live reload etc.

Open `http://localhost:8080` in your browser.

### Production

```bash
npm run build
npm start
```

This runs a production-ready express server that serves up a bundled and
minified version of the client.

Open `http://localhost:8080` in your browser.

### Tests

#### Single Run
```bash
$ npm run test
```

#### Watch Files
```bash
$ npm run test:watch
```

#### Coverage
```bash
$ npm run cover
```
