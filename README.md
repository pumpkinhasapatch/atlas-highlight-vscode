# Atlas script syntax grammar & highlighting

Grammar definitions and code syntax highlighting for the script insertion utility [Atlas](https://github.com/stevemonaco/Atlas/) by Steve Monaco "Klarth", and it's younger brother [abcde]().

Atlas is used in many video game reverse-engineering and fan translation projects. You can find [files on GitHub using Atlas](https://github.com/search?q=path%3A*.txt+%2F%5E%23ACTIVETBL%5C%28.%2B%5C%29%2F+NOT+is%3Afork&type=code&expanded_query=path%3A*.txt+%2F%5E%23ACTIVETBL%5C%28.%2B%5C%29%2F+NOT+is%3Afork) scripting. The Atlas script format and commands are described in the official [Atlas Reference guide](https://github.com/stevemonaco/Atlas/blob/master/docs/Atlas.pdf) documentation.

## Features

- Highlight Atlas/abcde commands in the `#COMMAND(args)` format.
- Square brackets and parenthesis stand out, commonly used for special values in the Table file.
- Angled brackets with a dollar sign used for raw hex values, such as `<$FF>`, are in purple.
- Make your Atlas scripts easier to read by color-coding different pieces of text.

Screenshot of the syntax highlighting VS Code extension with code from the [Doko Demo Issyo PSP English Translation Project](https://github.com/pumpkinhasapatch/dokodemo-psp-english):

![Screenshot from 2024-09-25 09-33-56](https://github.com/user-attachments/assets/9cf50bf5-6ea0-4a29-8d58-4d72105e1673)


## Installation

The main grammar code is located in the [syntaxes/atlas.tmLanguage.json](https://github.com/pumpkinhasapatch/atlas-highlight-vscode/blob/main/syntaxes/atlas.tmLanguage.json) file in [Textmate grammar](https://macromates.com/manual/en/language_grammars) format.


You can sideload this as an extension into Visual Studio Code or forks like VSCodium like most other extensions by downloading the source code as a .zip file, renaming the file extension to .vsix and importing it into VS Code.

## Issues

You can help improve Atlas grammar support by [opening an issue](https://github.com/pumpkinhasapatch/atlas-highlight-vscode/issues) on our GitHub page.

---

## For more information

* [Atlas repository on GitHub](https://github.com/stevemonaco/Atlas/)
* [Atlas on Romhacking.net](https://www.romhacking.net/utilities/224/) (outdated)

## License
This project was created by [pumpkinhasapatch](https://github.com/pumpkinhasapatch) and is licensed under the MIT Licnese. It uses some template code for VS Code extensions and Textmate grammars.
