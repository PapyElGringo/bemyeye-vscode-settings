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

See the dependencies

