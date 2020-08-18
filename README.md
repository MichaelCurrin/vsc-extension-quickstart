# VS Code Extension Quickstart
> Boilerplate for a new VS Code extension using TypeScript and NPM

This is a basic extension generated using the yeoman package, as covered below.

This project is just a hello world application and won't be modified much, so it can mainly serve as a reference for existing projects. Or as a template for new projects (with the difference that values have to be replaced manually rather than setup using a CLI).


## How to generate a quickstart

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

Install Node.js.

Clone this repo.

Run install (about 180 dependencies altogether)

```sh
$ npm install
```

## Usage

Use the Debug tab in VS Code to _Run Extension_.

See available script commands in [package.json] by running this:

```sh
$ npm run
...
```


## Features

Describe specific features of your extension including screenshots of your extension in action. Image paths are relative to this README file.

For example if there is an image subfolder under your extension project workspace:

\!\[feature X\]\(images/feature-x.png\)

> Tip: Many popular extensions utilize animations. This is an excellent way to show off your extension! We recommend short, focused animations that are easy to follow.


## Requirements

If you have any requirements or dependencies, add a section describing those and how to install and configure them.

## Extension Settings

Include if your extension adds any VS Code settings through the `contributes.configuration` extension point.

For example:

This extension contributes the following settings:

* `myExtension.enable`: enable/disable this extension
* `myExtension.thing`: set to `blah` to do something

## Known Issues

Calling out known issues can help limit users opening duplicate issues against your extension.

## Release Notes

Users appreciate release notes as you update your extension.

### 1.0.0

Initial release of ...

### 1.0.1

Fixed issue #.

### 1.1.0

Added features X, Y, and Z.

-----------------------------------------------------------------------------------------------------------

## Working with Markdown

**Note:** You can author your README using Visual Studio Code.  Here are some useful editor keyboard shortcuts:

* Split the editor (`Cmd+\` on macOS or `Ctrl+\` on Windows and Linux)
* Toggle preview (`Shift+CMD+V` on macOS or `Shift+Ctrl+V` on Windows and Linux)
* Press `Ctrl+Space` (Windows, Linux) or `Cmd+Space` (macOS) to see a list of Markdown snippets

### For more information

* [Visual Studio Code's Markdown Support](http://code.visualstudio.com/docs/languages/markdown)
* [Markdown Syntax Reference](https://help.github.com/articles/markdown-basics/)

**Enjoy!**


## License

Released under [MIT](/LICENSE).
