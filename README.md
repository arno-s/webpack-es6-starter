# webpack-starter-cli

```bash
npm install -g @vleesbrood/webpack-starter-cli
```

> a webpack config in a cli

## pre-requisites

- Node & NPM

## gotcha's

The cli assumes a folder layout like this:

```
 |- src/
 |- package.json
 |- .babelrc
 |- vlees.config.json
```

Use .babelrc to add babel presets!

```bash
# installing @babel/core is required if you need a custom preset
$ npm install --save @babel/core @babel/preset-env
```

```json
{
  "presets": [
    "@babel/preset-react"
  ]
}
```