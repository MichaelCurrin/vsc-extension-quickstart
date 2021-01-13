# Development
> Tips for developers using this repo

Make sure you follow the [Installation](installation.md) guide first.


## Run linter

```sh
$ npm run lint
```

## Run tests

```sh
$ npm test
```

That will also run the TypeScript compile and lint steps.

Note that you must exit all instances of VS Code to run the tests, or you'll get this error:

```
[main 2021-01-13T15:54:07.713Z] Running extension tests from the command line is currently
only supported if no other instance of Code is running.
```

When VS Code was closed, I found this step runs and gets stuck with the instance open.

You can also run tests with VS Code open using another approach. If you use the _Debug_ tab in VS Code, you can run _Extension Tests_, that will open up another VS Code window.


## Commands

See available script commands in [package.json](/package.json) by running this:

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
