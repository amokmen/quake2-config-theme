# Color theme for Quake 2 configuration files (dependency for syntax highlighting extension)

**ATTENTION!**

This is **not standalone** extension!

Must be used together with **syntax highlighting extension** --> [amokmen.quake2-config-syntax](https://marketplace.visualstudio.com/items?itemName=amokmen.quake2-config-syntax).

## Description

\- *Why this theme extension was created?*

\- Because if use **Quake II Syntax Highlighting extension** with any other VS Code Color Theme - there would be **limitations** in colorizing "q2config" language.

\- *What exactly do this theme extension?*

\- Is colorizing **text tokens**, which provided by **syntax extension**. Example: for all text tokens from **scope** with name "variable.q2config.cvars" there would be special foreground color and/or font attributes.

\- *I want to change colors or font attributes (italic, bold, underline, strikethrough)!*

\- Easy! Simply edit file with name "q2config-color-theme.json". This file would be at this location: for Linux `~/.vscode/extensions/amokmen.q2config-theme/themes/` or for Windows `%USERPROFILE%\.vscode\extensions\amokmen.q2config-theme/themes/`. And reload VS Code after editing.

\- *There is only Dark theme?*

\- Yes, I am lazy to create Light theme :)

## Table of matching scope name and applied style

How to understand scope names, read my [Scopes naming explanation](https://marketplace.visualstudio.com/items?itemName=amokmen.quake2-config-syntax#scopes-naming-explanation), please.

| Scope name                                         | Foreground color | Font style |
| -------------------------------------------------- | ---------------- | ---------- |
| support.function.q2config                          | #de8c07          | none       |
| support.function.q2config.commands.functions.q2pro | #a66803          | italic     |

Scope name;Foreground color;Font style
support.function.q2config;#de8c07;none
support.function.q2config.commands.functions.q2pro;#a66803;italic

## Developing (part of readme for Github users)

* Create coloring scheme: helping online [service](https://mycolor.space).
* Key combination to invoke modal window with TextMate scopes Inspector - at `.vscode/keybindings.json`
* Launch debug - press F5 - would open new VS Code window with test file.
* How to publish extension.
