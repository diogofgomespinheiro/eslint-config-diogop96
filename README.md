# Personal ESLint and Prettier config

## Whats included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- Import helpers plugin;
- JSX a11y plugin;
- Prettier;

## Setup

1. Install the dependencies

```
npm i -D eslint @diogop_96/eslint-prettier-config
```

2. Create a `.eslintrc.js` file extending the config:

```
{
  "extends": "@diogop_96/eslint-prettier-config/react"
}
```

3. Create a `.prettierrc.js` file extending the config:

```
module.exports = {
    ...require("@@diogop_96/eslint-prettier-config/prettier"),
    // your overwrite
    printWidth: 140,
    tabWidth: 4
};
```
