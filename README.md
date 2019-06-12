# eslint-config-kg
qmkg Eslint Recommond Configuration.

## Install

```bash
$ npm i eslint-config-kg -g
```

## How to use

`package.json`

```
{
  "eslintConfig": {
    "extends": "eslint-config-kg"
  },
  "eslintIgnore": [
    "/dev",
    "/node_modules",
    "/output"
  ]
}
```

## Use in VSCode

https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint