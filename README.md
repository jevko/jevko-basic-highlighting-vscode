# jevko-basic-highlighting

Basic syntax highlighting for Jevko in Visual Studio Code.

## Features

The most basic possible syntax highlighting for Jevko that works in Visual Studio Code.

![screenshot](screenshot.png)

<!-- ## Requirements

If you have any requirements or dependencies, add a section describing those and how to install and configure them. -->

<!-- ## Extension Settings

Include if your extension adds any VS Code settings through the `contributes.configuration` extension point.

For example:

This extension contributes the following settings:

* `myExtension.enable`: enable/disable this extension
* `myExtension.thing`: set to `blah` to do something -->

## Known Issues

There is an unfixable bug where only the lines that contains an opening bracket `[` in Jevko prefixes are properly highlighted.

Other lines look the same as suffixes.

This is impossible to workaround, because TextMate grammars are line-oriented, while Jevko is not.

However vscode allows more advanced extensions for semantic highlighting which have no such limitations. Once such an extension for Jevko is published, this one will be deprecated.

## Release Notes

Users appreciate release notes as you update your extension.

### 0.0.1

Initial version. Most basic highlighting works as well as possible.

## Installation

* To start using this extension with Visual Studio Code copy the folder that contains this repository into the `<user home>/.vscode/extensions` folder and restart Code.