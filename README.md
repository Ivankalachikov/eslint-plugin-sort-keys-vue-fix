# eslint-plugin-sort-keys-vue-fix-mod

Fork of eslint rule that sorts keys in objects (https://eslint.org/docs/rules/sort-keys) with autofix enabled compatible with vue order-in-components

## Installation

You'll first need to install [ESLint](https://eslint.org/):

```sh
npm i eslint --save-dev
```

Next, install `eslint-plugin-sort-keys-vue-fix-mod`:

```sh
npm install eslint-plugin-sort-keys-vue-fix --save-dev
```

## Usage

Add `sort-keys-vue-fix` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "sort-keys-vue-fix-mod"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "sort-keys-vue-fix-mod/sort-keys-vue-fix": "warn"
    }
}
```

## Supported Rules

For available config options, see official [vue/sort-keys](https://eslint.vuejs.org/rules/sort-keys.html) reference.
