# Dirosaki ESLint config

## Whats included?

- Airbnb TS config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Import Helpers;
- Prettier;

## Setup

1. Install the dependencies

```
yarn add -D eslint eslint-config-van-gogh
```

2. Create a `.eslintrc` file extending the config:

```json
{
	"extends": ["van-gogh", "van-gogh/import", "van-gogh/prettier"]
}
```
