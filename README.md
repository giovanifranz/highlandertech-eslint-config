# Rocketseat ESLint config

## Whats included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Airbnb
- Simple Import Sort
- Prettier;

## Setup

1. Install the dependencies
```
npm i -D eslint @highlandertech/eslint-config
```

2. Create a `.eslintrc.json` file extending the config:
```
{
  "extends": "@highlandertech/eslint-config/eslint"
}
```
> You can also use a `.eslintrc.js` instead of JSON if you prefer.

3. Create a `.prettierrc.js` file extending the config:
```
{
  module.exports = require("@highlandertech/eslint-config/prettier")
}
```