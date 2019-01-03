# @mighty-justice/tslint-config

[![npm Version](https://img.shields.io/npm/v/@mighty-justice/tslint-config.svg)](https://www.npmjs.com/package/@mighty-justice/tslint-config) [![Build Status](https://travis-ci.org/mighty-justice/tslint-config.svg?branch=master)](https://travis-ci.org/mighty-justice/tslint-config)

This package is a configuration preset for [TSLint](https://palantir.github.io/tslint). It contains a set of rules applied to most TypeScript projects at Mighty.


## Install

```sh
yarn add --dev @mighty-justice/tslint-config
```


## Usage

Add `@mighty-justice/tslint-config` to your project's TSLint configuration file. i.e.:

```json
{
  "extends": "@mighty-justice/tslint-config"
}
```

If possible, try not to override the preset unless you have a special reason.


## Release

To release:

```sh
npm run release
```

## License

MIT
