These are settings for ESLint and Prettier used by me.

## What it does

This setup lints your JavaScript code based on practices. Check the [.eslintrc.js](https://github.com/kelmancelis/eslint-config/blob/main/.eslintrc.js) file to see what is included. Feel free to override the rules that make sense for you.

## Installing

1. In your project folder, run:

```
npm i -D @kelmancelis/eslint-config # or yarn install --dev @kelmancelis/eslint-config
npx install-peerdeps --dev @kelmancelis/eslint-config
```

2. You will see several dependencies were installed. Now, create (or update) a `.eslintrc` file with the following content:

```js
{
  'extends': [
    '@kelmancelis'
  ]
}
```

3. Copy the [.prettierrc](https://github.com/kelmancelis/eslint-config/blob/main/.prettierrc) file from this repository into your project folder

---