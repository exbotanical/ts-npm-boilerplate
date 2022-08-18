# <project>

[![Coverage Status](https://coveralls.io/repos/github/exbotanical/<project>/badge.svg?branch=master)](https://coveralls.io/github/exbotanical/<project>?branch=master)
[![Continuous Deployment](https://github.com/exbotanical/<project>/actions/workflows/cd.yml/badge.svg)](https://github.com/exbotanical/<project>/actions/workflows/cd.yml)
[![Continuous Integration](https://github.com/exbotanical/<project>/actions/workflows/ci.yml/badge.svg)](https://github.com/exbotanical/<project>/actions/workflows/ci.yml)
[![npm version](https://badge.fury.io/js/<project>.svg)](https://badge.fury.io/js/<project>)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Table of Contents

- [Install](#install)
  - [Supported Environments](#support)
- [Documentation](#docs)

## <a name="install"></a> Installation

```bash
npm install <project>
```

OR

```bash
yarn add <project>
```

### <a name="support"></a> Supported Environments

`<project>` currently supports UMD, CommonJS (node versions >= 10), and ESM build-targets

Commonjs:

```js
const { isDefined } = require('<project>')
```

ESM:

```js
import { isDefined } from '<project>'
```

## <a name="docs"></a> Documentation

Full documentation can be found [here](https://exbotanical.github.io/<project>/<project>.html)
