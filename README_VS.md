## VS Packages

- Beautify (hookyQR)
- Debugger for Chrome (microsoft)
- ES7 React/Redux/Graphql (dsznajder)
- Import cost (wix)
- LevelUp Theme official (leveluptutorials)
- Material icon theme (philipp kief)
- vscode-icons (roberto huertas)
- ESLint (Dirk Baeumer)
- Prettier (Esben Petersen)
- Line Endings (Johnny Hartell)

### Install firacode font


[Link](https://github.com/tonsky/FiraCode/wiki/Linux-instructions)


### settings.json
```
{
    "editor.formatOnSave": true,
    "[javascript]": {
        "editor.formatOnSave": false
    },
    "files.trimTrailingWhitespace": true,
    "eslint.autoFixOnSave": true,
    "eslint.alwaysShowStatus": true,
    "prettier.disableLanguages": [
        "js"
    ],
    "files.autoSave": "onFocusChange",
    "editor.fontSize": 14,
    "editor.tabSize": 2,
    "editor.fontWeight": "400",
    "editor.cursorBlinking": "solid",
    "editor.rulers": [
        80
    ],
    "editor.fontFamily": "Operator Mono, Consolas, 'Courier New', monospace",
    "editor.fontLigatures": true,
    "terminal.integrated.fontSize": 12,
    "editor.renderWhitespace": "boundary",
    "workbench.colorCustomizations": {
        "editorWhitespace.foreground": "#FFD"
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
    "material-icon-theme.showUpdateMessage": false,
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

#### color theme: Dark+
