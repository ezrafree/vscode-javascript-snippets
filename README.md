# JavaScript Snippets

<p>
  <a href="https://marketplace.visualstudio.com/items?itemName=ezrafree.js-snippets">
    <img src="https://vsmarketplacebadges.dev/version/ezrafree.js-snippets.svg" alt="Version" />
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=ezrafree.js-snippets">
    <img src="https://vsmarketplacebadges.dev/installs/ezrafree.js-snippets.svg" alt="Installs" />
  </a>
</p>

This is a small collection of useful JavaScript and frontend snippets for VS Code.

## Install Instructions

This extension can be installed through the VS Code Marketplace:

[https://marketplace.visualstudio.com/items?itemName=ezrafree.js-snippets](https://marketplace.visualstudio.com/items?itemName=ezrafree.js-snippets)

## Features

### HTML

| Shortcut   | Command                                                               |
| ---------- | --------------------------------------------------------------------- |
| `html`       | an HTML boilerplate with tab stops                                           |
| `meta-og`     | OpenGraph meta tags                                                    |
| `meta-twitter`   | Twitter meta tags                           |
| `script-src`    | `<script src="${1}" ${2\|defer,async\|}></script>`                                                |
| `script`    | `<script></script>`                                                |
| `style`    | `<style></style>`                                                |
| `link-stylesheet` | `<link rel="stylesheet" href="$1">`   |
| `link-preload` | `<link rel="preload" href="${1:file}" as="${2\|font,image,script,style,fetch\|}" ${3\|crossorigin=''\|}>`   |
| `font-face` | a self-hosted `@font-face` block   |

### Console Logs

| Shortcut   | Command                                                               |
| ---------- | --------------------------------------------------------------------- |
| `cl`       | `console.log('foo: ', foo)`                                           |
| `clog`     | `console.log(foo)`                                                    |
| `cljson`   | `console.log(JSON.stringify(foo, null, 2))`                           |
| `clobj`    | `console.log({ foo })`                                                |
| `cleslint` | `// eslint-disable-next-line no-console \n console.log('$1: ', $1)`   |

### Eslint

| Shortcut            | Command                                                            |
| ------------------- | ------------------------------------------------------------------ |
| `esdisable`         | `/* eslint-disable @typescript-eslint/no-unused-vars */`           |
| `esdisablenextline` | `/* eslint-disable-next-line @typescript-eslint/no-unused-vars */` |

### Import Statements

| Shortcut | Command                                |
| -------- | -------------------------------------- |
| `imp`    | `import defaultExport from 'module'`   |
| `impn`   | `import { namedExport } from 'module'` |

### Jest Unit Tests

| Shortcut       | Command                               |
| -------------- | ------------------------------------- |
| `testfile`     | Unit test boilerplate                 |
| `testdescribe` | `describe('', () => {})`              |
| `testspec`     | `it('', () => {})`                    |
| `testassert`   | `expect(variable).toEqual(result)`    |

### React

| Shortcut                 | Command                            |
| ------------------------ | ---------------------------------- |
| `react-typescript`       | React component boilerplate        |
| `reactnative-typescript` | React Native component boilerplate |
| `use-effect`          | React useEffect hook boilerplate   |
