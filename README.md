# TSLint configuration for Storytel

Storytel coding conventions for TypeScript projects. Linting with [TSLint](https://palantir.github.io/tslint/).

## Getting started

Save the configuration

```shell
yarn add tslint-config-storytel
```
or
```shell
npm install --save-dev tslint-config-storytel
```

Create your `tslint.json`:
```json
{
  "extends": [
    "tslint-config-storytel"
  ]
}
```

And start linting (edit folders as appropriate):
```shell
tslint 'src/**/*.ts?(x)'
```

## Pro-tip

If you're adding this to an existing project, chances are there will be
a lot of linting errors. Let `tslint` fix what it can for you:

```shell
tslint --fix 'src/**/*.ts?(x)'
```

Inspect the changes (`git diff`) it made. Never trust anything.

It wont fix everything, but it will get you a bit on your way.
