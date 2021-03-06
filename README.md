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
| `cleslint` | `// eslint-disable-next-line no-console`<br>`console.log('$1: ', $1)` |

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

## Release Notes

### 0.0.4

Add snippets for default export and named export import statements

### 0.0.3

Add the `typescript` language mode

### 0.0.2

Add `javascriptreact` snippets to the `typescriptreact` language mode

### 0.0.1

Initial release of the extension

---

**Enjoy!**
