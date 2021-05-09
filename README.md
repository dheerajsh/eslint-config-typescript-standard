# ESLint and Prettier config

Recommended ESLint and Prettier for typescript codebase project.
The rules are strict and will help you to reduce runtime errors.

## Setup
1. install package with your preferred package manager
```
npm i eslint-config-typescript-standard
```
**OR**

```
yarn add eslint-config-typescript-standard
```


2. create or modify .eslintrc.js file with following content. and also update .prettierrc with .prettierrc file of this repository
```
{
  'extends': [
    'typescript-standard'
  ]
}
```
