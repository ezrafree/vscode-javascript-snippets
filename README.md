# JavaScript Snippets

This is a small collection of useful JavaScript snippets for VS Code.

## Features

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
| `useEffectHook`          | React useEffect hook boilerplate   |

## Install Instructions

This extension can be installed through the VS Code Marketplace:

[https://marketplace.visualstudio.com/items?itemName=ezrafree.js-snippets](https://marketplace.visualstudio.com/items?itemName=ezrafree.js-snippets)

For development, you can also install manually through git:

```sh
cd ~/.vscode/extensions
git clone git@github.com:ezrafree/vscode-javascript-snippets.git ezrafree.js-snippets
```

## Configuring

You may want to disable keywords in your configuration to make accessing snippets easier:

```json
{
  "[javascript]": {
    "editor.suggest.showKeywords": false
  },
  "[javascriptreact]": {
    "editor.suggest.showKeywords": false
  },
  "[typescript]": {
    "editor.suggest.showKeywords": false
  },
  "[typescriptreact]": {
    "editor.suggest.showKeywords": false
  }
}
```

Learn more about configuring snippets in the [VS Code IntelliSense documentation](https://code.visualstudio.com/docs/editor/intellisense#_customizing-intellisense).

## Known Issues

There are no known issues at this time, please reach out if you discover anything.
