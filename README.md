# JEC GlassCat CLI Project

[![JEC version](https://img.shields.io/badge/JEC-1.0-%23ba00ff.svg)](http://jecproject.org)
[![GlassCat version](https://img.shields.io/badge/GlassCat-1.0-%230a50ff.svg)](http://jecproject.org)
[![npm version](https://badge.fury.io/js/jec-glasscat-cli.svg)](https://www.npmjs.com/package/jec-glasscat-cli)
[![Apache 2.0](https://img.shields.io/hexpm/l/plug.svg)](https://www.apache.org/licenses/LICENSE-2.0)

The GlassCat CLI Project contains the command-line user interface for the GlassCat Aplication Server.

[![][jec-logo]][jec-url]

## Requirements

The JEC GlassCat CLI Project needs the following system parameters in order to work correctly:

- Node 6+
- npm 3+
- TypeScript 2+

## Installation

Set up the JEC GlassCat CLI module with:

```bash
$ npm install jec-glasscat-cli --save
```

## Running Tests

To execute all unit tests, use:

```bash
$ npm test
```

## API Reference

The API Reference documentation is not included into the JEC GlassCat CLI node module. To build the API reference documentation, use:

```bash
$ grunt doc
```

Documentation will be generated in the `docs/api-reference` repository.
The online version of the  API reference documentation will be available soon at the JEC Website.

The documentation generator is [TypeDoc](http://typedoc.org/)

## Update Release Notes

**Current stable release:** [1.0.7](CHANGELOG.md#jec-glasscat-cli-1.0.7)
 
For a complete listing of release notes for all JEC GlassCat CLI update releases, see the [CHANGELOG](CHANGELOG.md) file. 

## License
This JEC GlassCat CLI Project is licensed under Apache 2.0. Full license text is available in [LICENSE](LICENSE).

```
Copyright 2016-2018 Pascal ECHEMANN.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

[jec-url]: http://jecproject.org
[jec-logo]: https://raw.githubusercontent.com/jec-project/JEC/master/assets/jec-logos/jec-logo.png