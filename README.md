# Universal Gulp HTML Boilerplate
[![License: MIT](https://img.shields.io/badge/License-MIT-brightgreen.svg)](https://opensource.org/licenses/MIT) ![dependencies](https://img.shields.io/david/necheporenko/universal-gulp-html-boilerplate.svg?style=flat)

## Features

- Gulp 4
- SASS / SCSS
- Autoprefix, compile, concatenate, minify, lint
- Eslint, Prettier, Stylelint
- Livereload
- Placeholder CSS media queries
- Optimize images
- WebP
- Production mode

## Getting Started

CLONE THE GIT REPO:

```sh
git clone https://github.com/necheporenko/universal-gulp-html-boilerplate
cd universal-gulp-html-boilerplate
```

INSTALL YARN:

```js
npm install -g yarn
```

INSTALL DEPENDENCIES

```sh
yarn
```

START WORKFLOW:

```sh
yarn dev
```

PRODUCTION TEMPLATE

```sh
yarn build
```

## File Structure
```
├── dev               # Build files
├── dist              # Distribution files
├── src               # Source files
│ ├── components      # Components directory
│ ├── files           # Other files directory
│ ├── fonts           # Fonts directory
│ ├── images          # Images directory
│ ├── js              # JavaScript files
│ ├── libs            # Libs directory
│ ├── pages           # HTML files
│ └── styles          # Styles files
├── .editorconfig     # Editor configuration
├── .eslintrc         # Eslint configuration
├── .gitignore        # Git ignored files
├── .prettierrc       # Prettier configuration
├── .stylelintrc      # Stylelin configuration
├── LICENSE           # License agreements
├── gulpfile.js       # Gulp configuration
└── package.json      # Node packages
```
