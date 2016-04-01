# rc-component-tutorial
---

React RcComponent Component


[![NPM version][npm-image]][npm-url]
[![build status][travis-image]][travis-url]
[![Test coverage][coveralls-image]][coveralls-url]
[![gemnasium deps][gemnasium-image]][gemnasium-url]
[![npm download][download-image]][download-url]

[npm-image]: http://img.shields.io/npm/v/rc-rc-component.svg?style=flat-square
[npm-url]: http://npmjs.org/package/rc-rc-component
[travis-image]: https://img.shields.io/travis/react-component/rc-component.svg?style=flat-square
[travis-url]: https://travis-ci.org/react-component/rc-component
[coveralls-image]: https://img.shields.io/coveralls/react-component/rc-component.svg?style=flat-square
[coveralls-url]: https://coveralls.io/r/react-component/rc-component?branch=master
[gemnasium-image]: http://img.shields.io/gemnasium/react-component/rc-component.svg?style=flat-square
[gemnasium-url]: https://gemnasium.com/react-component/rc-component
[node-image]: https://img.shields.io/badge/node.js-%3E=_0.10-green.svg?style=flat-square
[node-url]: http://nodejs.org/download/
[download-image]: https://img.shields.io/npm/dm/rc-rc-component.svg?style=flat-square
[download-url]: https://npmjs.org/package/rc-rc-component


## Screenshots

<img src="" width="288"/>


## Development

```
npm install
npm start
```

## Example

http://localhost:8000/examples/


online example: http://react-component.github.io/rc-component/


## install


[![rc-rc-component](https://nodei.co/npm/rc-rc-component.png)](https://npmjs.org/package/rc-rc-component)


## Usage

```js
var RcComponent = require('rc-rc-component');
var React = require('react');
React.render(<RcComponent />, container);
```

## API

### props

<table class="table table-bordered table-striped">
    <thead>
    <tr>
        <th style="width: 100px;">name</th>
        <th style="width: 50px;">type</th>
        <th style="width: 50px;">default</th>
        <th>description</th>
    </tr>
    </thead>
    <tbody>
        <tr>
          <td>className</td>
          <td>String</td>
          <td></td>
          <td>additional css class of root dom node</td>
        </tr>
    </tbody>
</table>


## Test Case

```
npm test
npm run chrome-test
```

## Coverage

```
npm run coverage
```

open coverage/ dir

## License

rc-rc-component is released under the MIT license.
