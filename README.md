asset-builder
=============

[![Build Status](https://travis-ci.org/austinpray/asset-builder.svg?branch=master)](https://travis-ci.org/austinpray/asset-builder) [![Coverage Status](https://img.shields.io/coveralls/austinpray/asset-builder.svg?branch=master&style=flat)](https://coveralls.io/r/austinpray/asset-builder) [![Dependency Status](https://david-dm.org/austinpray/asset-builder.svg)](https://david-dm.org/austinpray/asset-builder) [![Code Climate](https://codeclimate.com/github/austinpray/asset-builder/badges/gpa.svg)](https://codeclimate.com/github/austinpray/asset-builder)

Feed me a [manifest file](help/spec.md) and I will give you globs.

[![NPM](https://nodei.co/npm/asset-builder.png?downloads=true)](https://nodei.co/npm/asset-builder/)

## Install

```bash
npm install asset-builder --save-dev
```

## Usage

```javascript
var manifest = require('asset-builder')('./assets/manifest.json');
```

## Help

- [Examples, troubleshooting tips](help/)
- [Manifest File Specification](help/spec.md)
- [View this module's API documentation](http://use-asset-builder.austinpray.com/api/)
- [Walk through the annotated source code](http://use-asset-builder.austinpray.com/docco/)
