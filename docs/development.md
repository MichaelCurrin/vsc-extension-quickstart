# Development
> Tips for developers using this repo

Make sure you follow the [Installation](installation.md) guide first.


## Run linter

```sh
$ npm run lint
```

## Run tests

This will also run the TypeScript compile step and the lint step.

```sh
$ npm test
```


## Commands

See available script commands in [package.json][] by running this:

```sh
$ npm run
```
```
Lifecycle scripts included in vsc-extension-quickstart:
  pretest
    npm run compile && npm run lint
  test
    node ./out/test/runTest.js

available via `npm run-script`:
  vscode:prepublish
    npm run compile
  compile
    tsc -p ./
  lint
    eslint src --ext ts
  watch
    tsc -watch -p ./
```


## Start the extension
> Run temporarily in debug mode

Open the _Debug_ tab in VS Code then click _Run Extension_.

That will run the extension in a sandboxed environment in a new window - the extension is not installed in other windows and you won't be able to use the extension after you close the window.

That will run the watch command which compiles the app and then watches the directory for changes.

If you want to install the extension globally and so that is persists, see the [Deploy](deploy.md) doc.

[package.json]: /package.json
