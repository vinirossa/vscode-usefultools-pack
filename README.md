# Useful Tools Extension Pack

<!-- [![Visual Studio Marketplace](https://img.shields.io/visual-studio-marketplace/v/vscode-usefultools-pack?color=success&label=Visual%20Studio%20Marketplace)](https://marketplace.visualstudio.com/items?itemName=vscode-usefultools-pack)  -->

A collection of useful extensions to increase your productivity while you code, created by [vinirossa](https://github.com/vinirossa)

## Included extensions
#### Visual
- [Dracula Refined](https://marketplace.visualstudio.com/items?itemName=mathcale.theme-dracula-refined)
- [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=pkief.material-icon-theme)
- [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer)
#### Tools
- [Project Manager](https://marketplace.visualstudio.com/items?itemName=alefragnani.project-manager)
- [Settings Sync](https://marketplace.visualstudio.com/items?itemName=shan.code-settings-sync)
- [Live Share](https://marketplace.visualstudio.com/items?itemName=ms-vsliveshare.vsliveshare)
- [SQLTools](https://marketplace.visualstudio.com/items?itemName=mtxr.sqltools)
- [Easy Snippet Maker](https://marketplace.visualstudio.com/items?itemName=tariky.easy-snippet-maker)
- [File Templates for VSCode](https://marketplace.visualstudio.com/items?itemName=bam.vscode-file-templates)
- [SVG Viewer](https://marketplace.visualstudio.com/items?itemName=cssho.vscode-svgviewer)
#### Personal Use
- [Code Time](https://marketplace.visualstudio.com/items?itemName=softwaredotcom.swdc-vscode)
- [Music Time for Spotify](softwaredotcom.music-time)

## Want to install only some extensions?
To install only some of the fonts, just edit the package.json file removing the unwanted extensionPack consequences and then follow the procedures below to install locally.

## How to develop and install locally
- Clone the repository
```bash
$ git clone https://github.com/vinirossa/vscode-usefultools-pack
```
- Install vsce
```bash
$npm install -g vsce
```
- Create the extension package
```bash
$vsce package
```
- Install the extension via the .vsix file
1. Open VS Code
2. Select Extensions from the menu
3. Click More > Install from VSIX...
4. Select the reloaded-extension-pack-x.x.x.vsix file
5. Click Reload Now to reload the VS Code

## For more information

* [See my Github](https://github.com/vinirossa)
