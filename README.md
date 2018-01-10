# BeMyEye Extensions Pack - Visual Studio Code's extensions for BeMyEye developers

This extension pack for Visual Studio Code adds extensions that are amazingly useful for Angular development and used by BeMyEye.

## Recommended Settings

Editor settings

```json
	"editor.formatOnSave": true,
	"editor.formatOnType": true,
	"javascript.implicitProjectConfig.experimentalDecorators": true,
	"editor.wordWrap": "on",
	"editor.tabSize": 2,
	"tslint.autoFixOnSave": true,
    "macros": {
        "save5Times": [
            "workbench.action.files.save",
            "workbench.action.files.save",
            "workbench.action.files.save",
            "workbench.action.files.save",
            "workbench.action.files.save"
        ]
    }
```

Keybindings settings

```json
	{
    "key": "ctrl+s",
    "command": "macros.save5Times"
  }
```

## Included

Here is the list of extensions the pack includes:

[Angular Follow Selector](https://marketplace.visualstudio.com/items?itemName=sanderledegen.angular-follow-selector) - Enables clicking on Angular selectors in your HTML files and being redirected to their component definition, as well as the other way around by clicking on templateUrl and styleUrls in your component.

[Angular Language Service](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template) - This extension provides a rich editing experience for Angular templates, both inline and external templates. This extension is brought to you by members of the Angular team. It is fantastic at helping write solid code in the html templates.

[Angular v5 Snippets](https://marketplace.visualstudio.com/items?itemName=johnpapa.Angular2) - Angular snippets that follow the official style guide, for TypeScript, templates, and RxJS.

[tslint](https://marketplace.visualstudio.com/items?itemName=eg2.tslint) - Integrates the tslint linter for the TypeScript language into VS Code. Extremely helpful at detecting and helping fix TypeScript issues.

[Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag) - Automatically add HTML/XML close tag, same as Visual Studio IDE or Sublime Text does.

[Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag) - Automatically rename paired HTML/XML tag, same as Visual Studio IDE does.

[Beautify](https://marketplace.visualstudio.com/items?itemName=HookyQR.beautify) - Beautify javascript, JSON, CSS, Sass, and HTML in Visual Studio Code.

[Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense) - Visual Studio Code plugin that autocompletes filenames. Hopefully, VS Code will bake this in at some point. Until then, this is a keeper.

[Angular Inline](https://marketplace.visualstudio.com/items?itemName=natewallace.angular2-inline) - Visual Studio Code language extension for javascript/typescript files that use Angular2.

