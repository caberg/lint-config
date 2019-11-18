# lint-config

## Introduction

This repository contains sample linting configs for .scss, .js and .ts files. Currently they are all based on recommended configs.

## How to use

### Installing

Copy all dev dependencies from `package.json` and copy to your own `package.json`. Don't forget to run `yarn install`.

### Base

Copy `.editorconfig`, `.nvmrc` and `.prettierrc.json` to your project root. Copy also all the needed scripts from `package.json` to run the linting and autofixing the problems. Do not forget to change the paths.

### SCSS

Copy the file `./scss/.stylelintrc.json` to your project root.

### JS

Copy the file `./js/.eslintrc.json` to your project root if you are using Javascript in your project.

### TS

Copy the file `./ts/.eslintrc.json` to your project root if you are using TypeScript in your project.

## VSCode extensions

You can install VSCode extensions for Prittier, Stylelint and ESLint. Make sure you change the config for "format on save" to true. This will automatically format your code.

## TODO

- Check how to make unified `.eslintrc.json` for JS and TS codebases
- Check what rules we need to update
- Update `.editorconfig` for `.php` files and more
- Add precommit hooks to fix/lint files.
