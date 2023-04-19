## Description

Project skeleton for Nest, already configured with eslint (strict rules to force a readable pattern), Prettier, Import Lint, Commit Lint, Conventional Commit, Commitizen and Lint Staged. A pre-commit hook runs to apply `eslint --fix` and `prettier --write`, if everything is ok you can answer the prompt questions to fill a conventional commit form. These steps help to maintain the code readable and without merge conflicts when two developers format the same file.

All the rules set in eslint were choosen by me, extending airbnb base and adding (a lot) of new rules.

## Technologies used

- [Nest](https://nestjs.com/)
- [Commitlint](https://commitlint.js.org/#/)
- [Commitizen](https://github.com/commitizen/cz-cli)
- [Eslint](https://eslint.org/)
- [Husky](https://github.com/typicode/husky)
- [Lint Staged](https://github.com/okonet/lint-staged)
- [Airbnb](https://github.com/airbnb/javascript)
  - [Airbnb Typescript](https://github.com/iamturns/eslint-config-airbnb-typescript)
- [Prettier](https://prettier.io/)
  - [Eslint Config](https://github.com/prettier/eslint-config-prettier)
  - [Eslint Plugin](https://github.com/prettier/eslint-plugin-prettier)
- [Import](https://github.com/import-js/eslint-import-resolver-typescript)
  - [Eslint typescript resolver](https://github.com/import-js/eslint-import-resolver-typescript)
  - [Eslint helper](https://github.com/Tibfib/eslint-plugin-import-helpers)
  - [Eslint no-relative-import plugin](https://github.com/MelvinVermeer/eslint-plugin-no-relative-import-paths)

## Installation

```bash
$ pnpm install
```
