# Webpack Boilerplate

## installation

1. `npm install` or `yarn`

## How to use

## as development

`npm run dev` or `yarn dev`

## as production

`npm run build` or `yarn build`

## Adding React

package `react react-dom`
package dev `@babel/preset-react`

_.babelrc_

```json
{
  "presets": ["@babel/preset-react"]
}
```

## Adding CSS loader

package dev `style-loader css-loader`

_build/webpack.base.js_
Remove comment of _cssLoader_
