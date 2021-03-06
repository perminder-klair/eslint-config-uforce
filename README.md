# Eslint Config Flying Rocket 🚀

#### An ESLint [Shareable Config](http://eslint.org/docs/developer-guide/shareable-configs) for the style I use and you may like too 🍕

## Install

```bash
yarn add eslint-config-uforce --dev
```

## Usage

Shareable configs are designed to work with the `extends` feature of `.eslintrc` files.
You can learn more about
[Shareable Configs](http://eslint.org/docs/developer-guide/shareable-configs) on the
official ESLint website.

Add this to your .eslintrc file:

```
{
  "extends": "uforce"
}
```

*Note: We omitted the `eslint-config-` prefix since it is automatically assumed by ESLint.*

You can override settings from the shareable config by adding them directly into your
`.eslintrc` file.

## Packages:
  * [eslint-config-airbnb](https://www.npmjs.com/package/eslint-config-airbnb)
  * [eslint-config-prettier](https://www.npmjs.com/package/eslint-config-prettier)
  * [eslint-plugin-compat](https://www.npmjs.com/package/eslint-plugin-compat)
  * [eslint-plugin-flowtype](https://www.npmjs.com/package/eslint-plugin-flowtype)
  * [eslint-plugin-import](https://www.npmjs.com/package/eslint-plugin-import)
  * [eslint-plugin-jest](https://www.npmjs.com/package/eslint-plugin-jest)
  * [eslint-plugin-jsx-a11y](https://www.npmjs.com/package/eslint-plugin-jsx-a11y)
  * [eslint-plugin-prettier](https://www.npmjs.com/package/eslint-plugin-prettier)
  * [eslint-plugin-react](https://www.npmjs.com/package/eslint-plugin-react)


## Custom Rules:
  * Use signgle quotes (prettier)
  * Use semicolons (prettier)
  * no-weak-types - No using Array and Object in flow ( only warning)
  * react-in-jsx-scope - Turned off because I use preact a lot with .js files
