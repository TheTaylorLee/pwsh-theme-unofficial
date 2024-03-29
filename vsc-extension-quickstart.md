# Welcome to your VS Code Extension

## What's in the folder

* This folder contains all of the files necessary for your color theme extension.
* `package.json` - this is the manifest file that defines the location of the theme file and specifies the base theme of the theme.
    * To debug a them the json file for the team must exist and it must be added to the package.json file as well.
* `/themes/*.json` Location of the them files

## Get up and running straight away

* Press `F5` to open a new window with your extension loaded.
* Open `File > Preferences > Color Themes` and pick your color theme.
* Identify token colors
    * Open a file that has a language associated. The languages' configured grammar will tokenize the text and assign 'scopes' to the tokens. To examine these scopes, invoke the `Developer: Inspect Editor Tokens and Scopes` command from the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P` on Mac).
* Identify GUI elements/colors
    * Open help and toggle developer tools.
    * Navigate to the styles section an applied color customizations can be viewed and changed to see the impact of modifying an element.

## Make changes

* Changes to the theme file are automatically applied to the Extension Development Host window.

## Adopt your theme to Visual Studio Code

* The token colorization is done based on standard TextMate themes. Colors are matched against one or more scopes.

To learn more about scopes and how they're used, check out the [color theme](https://code.visualstudio.com/api/extension-guides/color-theme) documentation.

[Theme Color Reference](https://code.visualstudio.com/api/references/theme-color)

## Install your extension

* To start using your extension with Visual Studio Code copy it into the `<user home>/.vscode/extensions` folder and restart Code.
* To share your extension with the world, read on https://code.visualstudio.com/docs about publishing an extension.

### New Environment Setup

## Setup Environment for publishing changes
- Use vscode to connect to wsl
- Use vscode terminal to proceed
- [Install Dependencies](https://learn.microsoft.com/en-us/windows/dev-environment/javascript/nodejs-on-wsl)
    - sudo apt install curl
    - curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/master/install.sh | bash
    - Restart wsl2 terminal
    - nvm install --lts
    - nvm install node
- git clone https://github.com/TheTaylorLee/pwsh-theme-unofficial
- cd pwsh-theme-unofficial
- npm install -g vsce

## Create a new theme repo
- npm install -g yo generator-code
- yo code
- select new color theme

## Publish Changes
- vsce login <publishername>
- vsce package
- vsce publish

### [Theme Builder gui](https://themes.vscode.one/)
- Useful for creating the initial theme template