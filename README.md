# Shimmering Bee: Zigbee Device Adapter - Rules

[![license](https://img.shields.io/github/license/shimmeringbee/zda-rules.svg)](https://github.com/shimmeringbee/zda-rules/blob/master/LICENSE)
[![standard-readme compliant](https://img.shields.io/badge/standard--readme-OK-green.svg)](https://github.com/RichardLitt/standard-readme)

>  JSON configuration rules for Shimmering Bee: ZDA.

## Table of Contents

- [Background](#background)
- [Usage](#usage)
- [Maintainers](#maintainers)
- [Contributing](#contributing)
- [License](#license)

## Background

Rules definition for none compliant Zigbee devices that do not follow ZCL implementation standards.

## Supported Zigbee Devices

Please see the included SUPPORTED.md documentation.

## Usage

These JSON files should be unmarshalled against `rules.Rule` in `shimmeringbee/zda`, and provided to the constructor
of the ZDA gateway.

## Maintainers

[@pwood](https://github.com/pwood)

## Contributing

Feel free to dive in! [Open an issue](https://github.com/shimmeringbee/zda-rules/issues/new) or submit PRs.

All Shimmering Bee projects follow the [Contributor Covenant](https://shimmeringbee.io/docs/code_of_conduct/) Code of Conduct.

## License

   Copyright 2019-2020 Shimmering Bee Contributors

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.