## VS Packages

- Beautify (hookyQR)
- Debugger for Chrome (microsoft)
- ES7 React/Redux/Graphql (dsznajder)
- Import cost (wix)
- LevelUp Theme official (leveluptutorials)
- Material icon theme (philipp kief)
- vscode-icons (roberto huertas)

### Install firacode font


[Link](https://github.com/tonsky/FiraCode/wiki/Linux-instructions)


### settings.json
```
{
    "editor.fontSize": 12,
    "editor.tabSize": 4,
    "editor.fontFamily": "Fira Code",
    "editor.fontLigatures": true,
    "terminal.integrated.fontSize": 12,
    "editor.renderWhitespace": "boundary",
    "workbench.colorCustomizations": {
        "editorWhitespace.foreground": "#FFD"
    },
    "editor.tokenColorCustomizations": {
        "textMateRules": [
            {
                "scope": [
                    "entity.other.attribute-name"
                ],
                "settings": {
                    "fontStyle": "italic",
                    "foreground": "#7cDD6e"
                },
            },
            {
                "scope": [
                    "comment"
                ],
                "settings": {
                    "fontStyle": "italic"
                }
            }
        ]
    },
    "files.associations": {
        "*.js": "javascriptreact"
    },
    "workbench.iconTheme": "material-icon-theme",
    "editor.multiCursorModifier": "ctrlCmd",
    "emmet.includeLanguages": {
        "javascript": "javascriptreact",
    },
    "emmet.triggerExpansionOnTab": true,
    "emmet.showExpandedAbbreviation": "always",
    "workbench.startupEditor": "newUntitledFile",
    "vsicons.dontShowNewVersionMessage": true,
    "material-icon-theme.showUpdateMessage": false
}
```
### keybindings.json
```
[
    {
    "key": "ctrl+alt+d",
    "command": "editor.action.copyLinesDownAction",
    "when": "editorTextFocus && !editorReadonly"
    }
]
```

### update VScode

```
wget https://vscode-update.azurewebsites.net/latest/linux-deb-x64/stable -O /tmp/code_latest_amd64.deb
sudo dpkg -i /tmp/code_latest_amd64.deb
```
