# Language-Cython for Visual Studio Code

Homepage: https://github.com/guyskk/language-cython-for-vscode 

**The grammar was copied from [MagicPython](https://github.com/MagicStack/MagicPython), with a little improvement.**

## Features

- Syntax highlighter for Cython

## Development

- https://code.visualstudio.com/api/working-with-extensions/testing-extension
- https://code.visualstudio.com/docs/extensions/publish-extension

## Publish to Vscode Marketplace

1. Bump version in `package.json`
2. Update `CHANGELOG.md`
3. Execute `vsce package` to build package
4. Log into [marketplace](https://marketplace.visualstudio.com/vscode) and upload the extension package

![publish-extension](https://raw.githubusercontent.com/guyskk/language-cython-for-vscode/master/images/publish-extension.png)

## Publish to open-vsx.org

1. Document https://github.com/eclipse/openvsx/wiki/Publishing-Extensions#how-to-publish-an-extension
2. Execute `ovsx publish --pat <token>` to build and publish package


**Enjoy!**
