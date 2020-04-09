# Translation Generator

A visual studio code extension for you to generate the translations without leaving the current file.

Forked from: https://github.com/thiagocordeirooo/generate-translation-vscode

## Usage

![Usage](/assets/ng-translation-generator.gif)

## Extension Settings

This extension contributes the following settings:

- `ng-translation-generator.path`: Path to find your i18n files.
- `ng-translation-generator.sort`: Sort object after inserting translation.
- `ng-translation-generator.replaceOnTranslate`: Replace the selected text in HTML files after generating a translation string.
- `ng-translation-generator.templateHtmlToReplace`: Template HTML to replace the selected text after generating a translation string. \n The string i18n will be replaced by the chosen key.
- `ng-translation-generator.flatFormat`: Generate json with flatten keys.
- `ng-translation-generator.convertCaseToPascal`: Force every new key into PascalCase format.
