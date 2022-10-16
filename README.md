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
npm i -D eslint @dfgp/eslint-prettier-config
```

2. Create a `.eslintrc.js` file extending the config:

```
{
  "extends": "@dfgp/eslint-prettier-config/react"
}
```

3. Create a `.prettierrc.js` file extending the config:

```
module.exports = {
    ...require("@dfgp/eslint-prettier-config/prettier"),
    // your overwrite
    printWidth: 140,
    tabWidth: 4
};
```
