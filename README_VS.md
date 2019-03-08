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
- Custom CSS and JS Loader (be5invis)
- One Monokai theme (monokai)

### Install firacode font


[Link](https://github.com/tonsky/FiraCode/wiki/Linux-instructions)


### settings.json
```
{
  "explorer.openEditors.visible": 0,
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
  "editor.tabSize": 2,
  "editor.fontSize": 16,
  "editor.cursorBlinking": "solid",
  "editor.rulers": [
    80
  ],
  "editor.fontFamily": "Operator Mono Light, Fira Code",
  "editor.fontLigatures": true,
  "terminal.integrated.fontSize": 13,
  "editor.renderWhitespace": "boundary",
  "workbench.colorCustomizations": {
    "editorWhitespace.foreground": "#FFD",
  },
  "files.associations": {
    "*.js": "javascript"
  },
  "workbench.iconTheme": "vscode-icons",
  "editor.multiCursorModifier": "ctrlCmd",
  "emmet.includeLanguages": {
    "javascript": "javascriptreact",
  },
  "emmet.triggerExpansionOnTab": true,
  "emmet.showExpandedAbbreviation": "always",
  "workbench.startupEditor": "newUntitledFile",
  "vsicons.dontShowNewVersionMessage": true,
  "editor.tokenColorCustomizations": {
    "[One Monokai]": {
      "variables": "#56b6c2",
      "textMateRules": [{
          "scope": "keyword.control",
          "settings": {
            "foreground": "#e06c75"
          }
        },
        {
          "scope": "keyword.operator",
          "settings": {
            "foreground": "#e06c75",
          },
        },
        {
          "scope": "storage.type.function.arrow.js",
          "settings": {
            "foreground": "#61afed"
          }
        },
        {
          "scope": "punctuation.definition.template-expression.begin.js",
          "settings": {
            "foreground": "#e5c07a"
          },
        },
        {
          "scope": "punctuation.definition.template-expression.end.js",
          "settings": {
            "foreground": "#e5c07a"
          },
        }
      ],
    },
    "keywords": {
      "foreground": "#61afef",
    },
  },
  "files.eol": "\n",
  "window.zoomLevel": -1,
  "explorer.confirmDragAndDrop": false,
  "workbench.colorTheme": "One Monokai",
  "vscode_custom_css.imports": ["file:///C:/Users/diego/.vscode/style.css"],
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

### styles.css
```
.mtk16 {
	font-family: "Fira Code";
}
```
