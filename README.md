# @devtea2027/nihil-eligendi-aperiam-nemo
[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)
[![Semantic Versioning 2.0.0](https://img.shields.io/badge/semver-2.0.0-brightgreen?style=flat-square)](https://semver.org/spec/v2.0.0.html)
[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg?style=flat-square)](https://conventionalcommits.org)
[![License](https://img.shields.io/github/license/Anadian/@devtea2027/nihil-eligendi-aperiam-nemo)](https://github.com/devtea2027/nihil-eligendi-aperiam-nemo/blob/main/LICENSE)
[![npm](https://img.shields.io/npm/v/@devtea2027/nihil-eligendi-aperiam-nemo)](https://www.npmjs.com/package/@devtea2027/nihil-eligendi-aperiam-nemo)
[![ci](https://github.com/devtea2027/nihil-eligendi-aperiam-nemo/actions/workflows/ci.yml/badge.svg)](https://github.com/devtea2027/nihil-eligendi-aperiam-nemo/actions/workflows/ci.yml)
[![Coverage Status](https://coveralls.io/repos/github/Anadian/@devtea2027/nihil-eligendi-aperiam-nemo/badge.svg?branch=main)](https://coveralls.io/github/Anadian/@devtea2027/nihil-eligendi-aperiam-nemo?branch=main)

> A micropackage formerly known as `application-log-winston-interface`: a wrapper around initialising Winston with Application-Log Standard levels, colours, and specific formats.
# Table of Contents
- [Background](#Background)
- [Install](#Install)
- [Usage](#Usage)
- [API](#API)
- [Contributing](#Contributing)
- [License](#License)
# Background
A simple module that exists primarily as a convenience to initialise [Winston](https://github.com/winstonjs/winston) the way I like.
# Install
Using [pnpm](https://pnpm.io/cli/add):
```bash
pnpm add --save @devtea2027/nihil-eligendi-aperiam-nemo
```
It can, of course, also be installed by [NPM](https://docs.npmjs.com/cli/v8/commands/npm-install) or [Yarn](https://yarnpkg.com/getting-started/usage) using the normal methods.
# Usage
# API
```js
import * as ApplicationLogWinstonInterface from '@devtea2027/nihil-eligendi-aperiam-nemo';

try{
	var Logger = ApplicationLogWinstonInterface.initWinstonLogger( 'base_name.log', './log/directory' );
} catch(error){
	//
}
```
# Contributing
Changes are tracked in [CHANGELOG.md](CHANGELOG.md).
# License
MIT ©2021 Anadian

SEE LICENSE IN [LICENSE](LICENSE)

[![Creative Commons License](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)This project's documentation is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
