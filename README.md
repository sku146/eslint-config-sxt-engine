# eslint-config-sxt-engine
Collection of ESLint rules to use for all the development environments (ex: nodejs, react, webpack, etc..,)

## Installation

You'll install `eslint-config-sxt-engine`:

```
$ npm install eslint-config-sxt-engine --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `eslint-config-sxt-engine` globally.

## Usage

Add `sxt-engine` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-config-` prefix:

```json
{
    "extends": [
        "sxt-engine"
    ]
}
```

## For React

```json
{
    "extends": [
        "sxt-engine/react"
    ]
}
```

## For Jasmine

```json
{
    "extends": [
        "sxt-engine/jasmine"
    ]
}
```


## For Lodash 

```json
{
    "extends": [
        "sxt-engine/lodash"
    ]
}
```

## For Jest 

```json
{
    "extends": [
        "sxt-engine/jest"
    ]
}
```

## For Webpack 

```json
{
    "extends": [
        "sxt-engine/webpack"
    ]
}
```

## License

[MIT](http://www.opensource.org/licenses/mit-license.php)