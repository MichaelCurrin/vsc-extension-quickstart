# Start fresh
> How to generate a new extension from scratch

These were the steps followed to create this project. If you don't want to use this repo directly, you can create a new project using an official template.

For more info, see the [Your First Extension][] doc page.

## Pick a repo workspace

You don't need to create a new directory. Start from your usual repos directory.

```sh
$ cd ~/repos
```

## Generate the extension

```sh
$ npx yo code
```

Enter answers in the REPL - for example:

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

## Open

Open your new project in VS Code

```sh
$ code helloworld
```

## How to run it

Now you can start the extension with the debugger in an isolated environment

To do this, follow the steps in the [usage](usage.md) section of this quickstart guide. They will still apply.


[Your First Extension]: https://code.visualstudio.com/api/get-started/your-first-extension
