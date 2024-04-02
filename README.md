# ESLint config

## Whats included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- ESLint;
- Prettier;
- Tailwind CSS;

## Setup

## Required >= React v18.0

### React (without Next.js)

Install dependencies:
```
npm install eslint prettier prettier-plugin-tailwindcss eslint-plugin-prettier eslint-config-prettier eslint-plugin-jsx-a11y eslint-plugin-n eslint-plugin-import eslint-plugin-promise eslint-plugin-react eslint-plugin-react-hooks babel-eslint eslint-config-standard eslint-plugin-standard --save-dev
```
OR
```
yarn add eslint prettier prettier-plugin-tailwindcss eslint-plugin-prettier eslint-config-prettier eslint-plugin-jsx-a11y eslint-plugin-n eslint-plugin-import eslint-plugin-promise eslint-plugin-react eslint-plugin-react-hooks babel-eslint eslint-config-standard eslint-plugin-standard --dev
```

Inside `.eslintrc.json`
```
{
  Copy content from reactWithoutNextJs.json
}
```

### Node.js

Install dependencies:
```
npm install eslint prettier eslint-plugin-prettier eslint-config-prettier eslint-plugin-n eslint-plugin-import eslint-plugin-promise babel-eslint eslint-config-standard eslint-plugin-standard --save-dev
```
OR
```
yarn add eslint prettier eslint-plugin-prettier eslint-config-prettier eslint-plugin-n eslint-plugin-import eslint-plugin-promise babel-eslint eslint-config-standard eslint-plugin-standard --dev
```

Inside `.eslintrc.json`
```
{
  Copy content from nodeJs.json
}
```
