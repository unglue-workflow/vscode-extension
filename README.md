# Unglue Visual Studio Code Extension

An Unglue extension for Visual Studio Code. This extension will enable unglue file syntax (which is actually json syntax) for `.unglue` config files. In future it will provide the possible array keys while typing (`js`, `css`, `options` and `sprite).

Fore more informations:

Documentation: [https://docs.unglue.io](https://docs.unglue.io)
Project Website: [https://unglue.io](https://unglue.io)

## Development notes

Some general informations about vscode extension development:

+ Getting started: https://code.visualstudio.com/api/get-started/your-first-extension
+ Language Extensions Example: https://github.com/Microsoft/vscode-extension-samples/tree/master/language-configuration-sample
+ Language Config: https://code.visualstudio.com/api/language-extensions/language-configuration-guide

Compile the package for an upload:

```
npm install -g vsce
```

and run 

```
vsce package
```

You can now upload the generated file.
