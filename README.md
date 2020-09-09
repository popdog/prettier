# Popdog ♥️ Prettier

Shared Prettier config! This helps us standardize formatting across multiple projects.

## How do I use this?

1. Install Prettier and this config package.
You may need to add the `@popdog` scope to your npm creds, [instructions here](https://github.com/popdog/web/blob/master/README.md)

    ```
    yarn add prettier @popdog/prettier
    ```

1. Add this line to your package.json

    ```
    "prettier": "@popdog/prettier"
    ```

1. Set up Prettier with your editor: https://prettier.io/docs/en/editors.html

1. Enjoy your new formatting!

## How do I publish this?

1. Bump the `version` in `package.json`

1. Tag a new release on github using the new version

1. Let github actions do the magic :)