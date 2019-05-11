# vscodemq2 README
Macroquest2 Language Plugin Visual Studio Code

Tons of work, consider a [DONATION](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=XP8Y6YRUAQJZ4&currency_code=USD&source=url)

## Features
1. Highlighting for most MQ2 commands. It is very aggressive at finding errors. 
2. Custom Icon included - view .\fileicons\README.md for details on installing it (will not work by default because VSCode does not support extending icon themes, only replacing them)

Autocomplete is in the works, but not ready for release.
## Requirements
Microsoft's VSCode, you can download it absolutely free on the [Visual Studio website](https://code.visualstudio.com/Download), available for Windows, Linux, and the Mac.

Install from VSCode Marketplace
To manually install, simply navigate to ~/.vscode/extensions (or in Windows, %USERPROFILE%\.vscode\extensions and expand the zip from git hub OR execute git clone https://github.com/djohnsonbaugh/vscodemq2macro.git. The changes in VSCode are automatic after a VSC restart.

Custom Icon requires "vscode-icons" extension.

## Known Issues
EQ Client Commands - This does not validate EQ commands at all. It identifies various EQ commands but then allows pretty much any sort of space delimited input without trying to identify errors.

MQ2 Commands - A subset of commands are supported, if I missed a key command you actually use, submit a request on issues 

MQ2 Plugin Commands - not validated currently, but some are recognized. Add issue if you feel explicit support is warranted.

Define - If you do a #define statement, it will probalby look like an error. (havent decided how to deal with this yet)

## Release Notes
Refer to the changelog.md