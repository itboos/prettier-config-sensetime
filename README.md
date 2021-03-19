# prettier-config-sensetime

> Sensetime DCP shared config for prettier.

## Installation

```console

npx install prettier-config-sensetime -D
```

## Usage

Set your .prettierrc config to:

```
"prettier-config-sensetime"
```

### Extending the config

Note: This method does not offer a way to extend the configuration to overwrite some properties from the shared configuration. If you need to do that, import the file in a `.prettierrc.js` file and export the modifications, e.g:

```javascript
module.exports = {
  ...require("prettier-config-sensetim"),
  semi: false,
  // 覆盖掉旧的配置
};
```

## [License](LICENSE)
