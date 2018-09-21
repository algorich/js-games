# js-games

Generated by [OSS Project Generator](http://bit.ly/generator-oss-project).

[![Travis Status][travis-badge]][travis-url]
[![AppVeyor Status][appveyor-badge]][appveyor-url]
[![CircleCI Status][circleci-badge]][circleci-url]
[![Coveralls Status][coveralls-badge]][coveralls-url]
[![NPM Version][npm-badge]][npm-url]
[![License][license-badge]][license-url]

> An awesome project

Long description.

## Installation

Install package

```bash
$ npm install --save js-games
```

## Usage

Say `It works!`

```js
const lib = require('js-games');

lib.hello((err, message) => {
  if (err) return console.error(err);

  console.log(message);
});
```

## Development

- Cloning the repo

```bash
$ git clone https://github.com/hrsalles/js-games.git
```

- Installing dependencies

```bash
$ npm install
```

- Running scripts

| Action                                   | Usage               |
| ---------------------------------------- | ------------------- |
| Starting development mode                | `npm start`         |
| Linting code                             | `npm run lint`      |
| Running unit tests                       | `npm run jest`      |
| Running code coverage                    | `npm run coverage`  |
| Running lint + tests                     | `npm test`          |
| Sending coverage results to Coveralls.io | `npm run coveralls` |

## Author

[Max Salles](https://twitter.com/hrsalles)

## License

[MIT](https://github.com/hrsalles/js-games/blob/master/LICENSE)

[travis-badge]: https://travis-ci.org/hrsalles/js-games.svg?branch=master
[travis-url]: https://travis-ci.org/hrsalles/js-games
[appveyor-badge]: https://ci.appveyor.com/api/projects/status/github/hrsalles/js-games?branch=master&svg=true
[appveyor-url]: https://ci.appveyor.com/project/hrsalles/js-games
[circleci-badge]: https://circleci.com/gh/hrsalles/js-games/tree/master.svg?style=shield
[circleci-url]: https://circleci.com/gh/hrsalles/js-games
[coveralls-badge]: https://coveralls.io/repos/github/hrsalles/js-games/badge.svg?branch=master
[coveralls-url]: https://coveralls.io/github/hrsalles/js-games?branch=master
[npm-badge]: https://img.shields.io/npm/v/js-games.svg
[npm-url]: https://www.npmjs.com/package/js-games
[license-badge]: https://img.shields.io/github/license/hrsalles/js-games.svg
[license-url]: https://opensource.org/licenses/MIT
