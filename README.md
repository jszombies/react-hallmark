# React Hallmark

[![Npm package](https://img.shields.io/npm/v/react-hallmark.svg?style=flat)](https://npmjs.com/package/react-hallmark)
[![Build Status](https://travis-ci.org/jszombies/react-hallmark.svg?branch=develop)](https://travis-ci.org/jszombies/react-hallmark)
[![Dependency Status](https://david-dm.org/jszombies/react-hallmark.svg)](https://david-dm.org/jszombies/react-hallmark)

## Intro

The component represent the tiny search/highlight React component.
No dependencies and redundant wrappers. Could be just copied from source code or used as an example of React component library

## Example 

```js
  <Items
    items={array}
    query={this.state.query}
    theme={theme}
    nothingView="Nothing to show"
  />
```

## API 

| property | type | default | note |
| -------- | ---- | ------- | ---- |
| `items` | shape | required | { label, link, [children]} |
| `query` | string | required | search pattern |
| `limit` | number | 10 | max count of items |
| `nothingView` | component/string | null | shows if no matches |
| `theme` | share | null | styles for components { item, empty} |

## Engines

* Yarn
* npm
* React