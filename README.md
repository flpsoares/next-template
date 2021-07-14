This is a model of a project using [NextJS](https://nextjs.org/), [TypeScript](https://www.typescriptlang.org/), [Styled-Components](https://styled-components.com/), [ESLint](https://eslint.org/), [Prettier](https://prettier.io/), and [Husky](https://www.npmjs.com/package/husky) with [conventional commits](https://github.com/conventional-changelog/commitlint).

## Getting Started

First, you must run 2 commands before starting the development server

```bash
yarn husky install
# and
yarn husky add .husky/commit-msg 'npx --no-install commitlint --edit "$1"'
```

After executing these 2 commands, execute:

```bash
yarn dev
```
