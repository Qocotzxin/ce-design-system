## Personal Design System

### Variables

- This repo exposes (for now) a single css file which contains css variables to use in different projects.

## Usage

`pnpm tokens` - This generates the css file that contains all the variables.

## How it works

- Design tokens (css variables) are generated via [Style Dictionary](https://amzn.github.io/style-dictionary/#/) based on the config file located in `design-tokens/config.json` which takes every json file within `data` dir and creates the variables by merging all declarations.
