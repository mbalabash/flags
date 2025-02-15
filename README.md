# NodeSecure Flags
![version](https://img.shields.io/badge/dynamic/json.svg?url=https://raw.githubusercontent.com/NodeSecure/flags/master/package.json&query=$.version&label=Version)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/NodeSecure/flags/commit-activity)
[![Security Responsible Disclosure](https://img.shields.io/badge/Security-Responsible%20Disclosure-yellow.svg)](https://github.com/nodejs/security-wg/blob/master/processes/responsible_disclosure_template.md
)
[![mit](https://img.shields.io/github/license/Naereen/StrapDown.js.svg)](https://github.com/NodeSecure/flags/blob/master/LICENSE)
![build](https://img.shields.io/github/workflow/status/NodeSecure/flags/Node.js%20CI)

NodeSecure security flags.

## Requirements
- [Node.js](https://nodejs.org/en/) v14 or higher

## Getting Started

This package is available in the Node Package Repository and can be easily installed with [npm](https://docs.npmjs.com/getting-started/what-is-npm) or [yarn](https://yarnpkg.com).

```bash
$ npm i @nodesecure/flags
# or
$ yarn add @nodesecure/flags
```

## Usage example

```js
import { getFlags, getManifest, eagerFetchFlagFile } from "@nodesecure/flags";

// Return a Set of flags title
const flags = getFlags();

// Return the manifest file
const manifest = getManifest();

const HTML = await eagerFetchFlagFile("hasBannedFile.html");
```

## API

See TypeScript definition file.


## Contributors ✨

<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-3-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://www.linkedin.com/in/thomas-gentilhomme/"><img src="https://avatars.githubusercontent.com/u/4438263?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Gentilhomme</b></sub></a><br /><a href="https://github.com/NodeSecure/flags/commits?author=fraxken" title="Code">💻</a> <a href="https://github.com/NodeSecure/flags/commits?author=fraxken" title="Documentation">📖</a> <a href="https://github.com/NodeSecure/flags/pulls?q=is%3Apr+reviewed-by%3Afraxken" title="Reviewed Pull Requests">👀</a> <a href="#security-fraxken" title="Security">🛡️</a> <a href="https://github.com/NodeSecure/flags/issues?q=author%3Afraxken" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://github.com/Kawacrepe"><img src="https://avatars.githubusercontent.com/u/40260517?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Vincent Dhennin</b></sub></a><br /><a href="https://github.com/NodeSecure/flags/commits?author=Kawacrepe" title="Code">💻</a> <a href="https://github.com/NodeSecure/flags/commits?author=Kawacrepe" title="Documentation">📖</a> <a href="https://github.com/NodeSecure/flags/pulls?q=is%3Apr+reviewed-by%3AKawacrepe" title="Reviewed Pull Requests">👀</a> <a href="https://github.com/NodeSecure/flags/issues?q=author%3AKawacrepe" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://github.com/Rossb0b"><img src="https://avatars.githubusercontent.com/u/39910164?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Nicolas Hallaert</b></sub></a><br /><a href="https://github.com/NodeSecure/flags/commits?author=Rossb0b" title="Documentation">📖</a></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

## License
MIT
