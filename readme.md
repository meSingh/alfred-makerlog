# MakerlogFlow

MakerlogFlow is Alfred Workflow that lets you to add new todo, inprogress & done tasks to [Makerlog](https://getmakerlog.com) directly using [makerlog-cli](https://github.com/MihaiVoinea/makerlog-cli)..

## Install

To install MakerlogFlow, install latest version of Makerlog CLI by running this command:

```
$ npm install -g makerlog-cli
```

Authenticate yourself with your Makerlog account using this command:

```
$ makerlog login --username "your_username" --password "your_password"
```
> makerlog-cli does not store your username or password, it only uses them to get a token from Makerlog.

Then download the [latest version here](#) & open it in Alfred to install this workflow.

## Usage

### TODO
In Alfred, type `todo`, <kbd>Enter</kbd>, and some text, to create a todo task in makerlog.

![todo](/screenshots/todo.png)

### IN PROGRESS
In Alfred, type `inprogress`, <kbd>Enter</kbd>, and some text, to create a inprogress task in makerlog.

![inprogress](/screenshots/inprogress.png)

### DONE
In Alfred, type `done`, <kbd>Enter</kbd>, and some text, to create a done task in makerlog.

![done](/screenshots/done.png)

## License

[MIT](license.md) © [Mandeep Singh](https://www.msingh.com)
