# Prettier config

Configuration for the [Prettier](https://prettier.io) code formatter.

## Installation

```sh
yarn add --dev @muhortov/prettier-config
```

## Usage

To enable prettier in your project add the `prettier` key to your `package.json` file:

```js
{
  // ...
  "prettier": "@muhortov/prettier-config"
}
```

To be able to format your files add the following command to the `package.json` file

```js
{
  // ...
  "scripts": {
    // ...
    "format": "prettier --write '**/*.{ts,tsx,js,jsx,vue,json,html,css,sass,scss,less,md,yaml,yml}'"
  }
}
```

You can now run `yarn format` to format your code.
