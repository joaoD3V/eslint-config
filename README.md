# Joao Silva ESLint config

## Whats included?

### ReactJS/NextJS

#### ESLint:

- React/Next plugin;
- React Hooks plugin;
- TypeScript;
- JSX a11y plugin;
- Prettier;

#### Prettier:

- trailingComma: 'es5';
- semi: true;
- singleQuote: true;
- endOfLine: 'auto';


### NodeJS

- TypeScript;
- Prettier;

#### Prettier:

- trailingComma: 'es5';
- semi: true;
- singleQuote: true;
- endOfLine: 'auto';

### React Native

#### ESLint:

- React plugin;
- React Hooks plugin;
- TypeScript;
- Prettier;

#### Prettier:

- trailingComma: 'es5';
- semi: true;
- singleQuote: true;
- endOfLine: 'auto';

## Setup

1. Install the dependencies
```
npm i -D eslint @joaod3v/eslint-config
```

2. Create a `.eslintrc.json` file extending the config:

**NextJS config also serve to ReactJS!**

```
{
  "extends": "@joaod3v/eslint-config/next"
  // "extends": "@joaod3v/eslint-config/node"
  // "extends": "@joaod3v/eslint-config/react-native"
}
```

> You can also use a `.eslintrc.js` instead of JSON if you prefer.