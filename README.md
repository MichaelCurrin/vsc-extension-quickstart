# VS Code Extension Quickstart
> Boilerplate for a new VS Code extension using TypeScript and NPM

[![GitHub tag](https://img.shields.io/github/tag/MichaelCurrin/vsc-extension-quickstart)](https://github.com/MichaelCurrin/vsc-extension-quickstart/tags/?include_prereleases&sort=semver)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue)](#license)

[![Use this template](https://img.shields.io/badge/Use_this_template-2ea44f?style=for-the-badge)](https://github.com/MichaelCurrin/vsc-extension-quickstart/generate)


This project covers the outline of basic VS Code extension and was generated using the `yeoman` NPM package, as covered below in [How to generate a new extension from scratch](#how-to-generate-a-new-extension-from-scratch).

For more info on developing extensions in VS Code, see the [Extension Overview](https://code.visualstudio.com/api) section of the docs.

This project is just a hello world application and won't be modified much, so it can mainly serve as a reference for existing projects. Or as a template for new projects (with the difference that values have to be replaced manually rather than setup using a CLI).


## How to generate a new extension from scratch

These were the steps followed to create this project. If you don't want to use this repo directly, you can create your own from scratch.

For more info, see the [Your First Extension](https://code.visualstudio.com/api/get-started/your-first-extension) doc page.

You don't need to create a new directory. Start from your usually repos directory.

```sh
$ cd repos
```

```sh
$ npx yo code
```

Enter answers in the REPL.

e.g.

```
# ? What type of extension do you want to create? New Extension (TypeScript)
# ? What's the name of your extension? HelloWorld
### Press <Enter> to choose default for all options below ###

# ? What's the identifier of your extension? helloworld
# ? What's the description of your extension? LEAVE BLANK
# ? Initialize a git repository? Yes
# ? Which package manager to use? npm
```

That will also install packages for you.

Then finally open the new project.

```sh
$ code helloworld
```

For setting up this existing repo, see below.


## Installation

Install [Node.js](https://gist.github.com/MichaelCurrin/aa1fc56419a355972b96bce23f3bccba).

Clone this repo.

```sh
$ git clone git@github.com:MichaelCurrin/vsc-extension-quickstart.git
```

Run install.

```sh
$ npm install
```

### What is the node modules footprint?

There are 11 dev dependencies. Four of those are just `@types/...` and there are no prod dependencies.

You'll end up with about 180 dependencies altogether.


## Usage


### Run linter

```sh
$ npm run lint
```

### Run tests

This will also run the TypeScript compile step and the lint step.

```sh
$ npm test
```

### Commands

See available script commands in [package.json] by running this:

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

### Run the extension

Use the _Debug_ tab in VS Code and click _Run Extension_. That will run the extension in a sandboxed environment in a new window and then remove it when closing the window.

This will run the watch command which compiles the app and then watches the directory for changes.

## Deployment

You can package your extension to be installed globally and shared with others.

You can also publish the extension to VS Code marketplace.

These steps are not covered in this project.


## License

Released under [MIT](/LICENSE).
