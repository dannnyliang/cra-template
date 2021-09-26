# cra-template-typescript

This is the official TypeScript template for [Create React App](https://github.com/facebook/create-react-app).

To use this template, add `--template @dannnyliang/cra-template-typescript` when creating a new app.

For example:

```sh
npx create-react-app my-app --template @dannnyliang/cra-template-typescript

# or

yarn create react-app my-app --template @dannnyliang/cra-template-typescript
```

For more information, please refer to:

- [Getting Started](https://create-react-app.dev/docs/getting-started) – How to create a new app.
- [User Guide](https://create-react-app.dev) – How to develop apps bootstrapped with Create React App.

### Custom config
- use [import-sort-cli](https://github.com/renke/import-sort#readme) to group and sort modules.
- use [eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) to run prettier as an ESLint rule.
- use [husky](https://github.com/typicode/husky) v6 to run `lint-staged` before commit.

### Scripts
- `cz`: make commit messages conventional with [cz-conventional-changelog](https://github.com/commitizen/cz-conventional-changelog) adapter.
- `lint-staged`: use [lint-staged](https://github.com/okonet/lint-staged) to run linters or foramtter to unify the coding styling.
