{
  "workbench.editorAssociations": {
    "*.copilotmd": "vscode.markdown.preview.editor",
    "*.db": "sqlite-viewer.view"
  },
  "[python]": {
    "editor.defaultFormatter": "ms-python.autopep8",
    "editor.formatOnSave": true
  },
  "breadcrumbs.enabled": false,
  "window.zoomLevel": 0,
  "editor.formatOnSave": true,
  "workbench.statusBar.visible": false,
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.wordWrap": "on",
  "explorer.confirmDelete": false,
  "python.createEnvironment.trigger": "off",
  "git.enableSmartCommit": true,
  "files.autoSave": "afterDelay",
  "explorer.confirmDragAndDrop": false,
  "explorer.fileNesting.patterns": {
    "*.ts": "${capture}.js",
    "*.js": "${capture}.js.map, ${capture}.min.js, ${capture}.d.ts",
    "*.jsx": "${capture}.js",
    "*.tsx": "${capture}.ts",
    "tsconfig.json": "tsconfig.*.json",
    "package.json": "package-lock.json, yarn.lock, pnpm-lock.yaml, bun.lockb, bun.lock",
    "*.sqlite": "${capture}.${extname}-*",
    "*.db": "${capture}.${extname}-*",
    "*.sqlite3": "${capture}.${extname}-*",
    "*.db3": "${capture}.${extname}-*",
    "*.sdb": "${capture}.${extname}-*",
    "*.s3db": "${capture}.${extname}-*"
  },
  "workbench.colorTheme": "Tokyo Night",
  "workbench.iconTheme": "material-icon-theme",
  "git.confirmSync": false,
  /*
    TODO Tree - Configuração aprimorada
*/
  "todo-tree.general.tags": [
    "TODO",
    "BUG",
    "HACK",
    "FIXME",
    "README",
    "XXX",
    "[ ]",
    "[x]",
    "!!!",
    "!!",
    "!"
  ],
  "todo-tree.tree.autoRefresh": true,
  "todo-tree.tree.groupByTag": true,
  "todo-tree.tree.hideIconsWhenGroupedByTag": false,
  "todo-tree.tree.showCountsInTree": true,
  "todo-tree.tree.hideFromTree": ["[x]"],
  "todo-tree.highlights.customHighlight": {
    "TODO": {
      "icon": "check",
      "foreground": "#FFD700",
      "background": "#333300",
      "type": "text"
    },
    "README": {
      "icon": "eye",
      "foreground": "#1E90FF",
      "background": "#001F3F",
      "type": "text"
    },
    "BUG": {
      "icon": "bug",
      "foreground": "#FF4500",
      "background": "#330000",
      "type": "text"
    },
    "HACK": {
      "icon": "tools",
      "foreground": "#FF8C00",
      "background": "#332100",
      "type": "text"
    },
    "FIXME": {
      "icon": "flame",
      "foreground": "#DC143C",
      "background": "#330013",
      "type": "text"
    },
    "XXX": {
      "icon": "x",
      "foreground": "#8B0000",
      "background": "#330000",
      "type": "text"
    },
    "[ ]": {
      "icon": "issue-draft",
      "foreground": "#32CD32",
      "background": "#002200",
      "type": "text"
    },
    "[x]": {
      "icon": "issue-closed",
      "foreground": "#808080",
      "background": "#202020",
      "type": "text"
    },
    "!!!": {
      "icon": "alert",
      "foreground": "#FF0000",
      "background": "#330000",
      "type": "text"
    },
    "!!": {
      "icon": "copilot-warning",
      "foreground": "#FFA500",
      "background": "#332100",
      "type": "text"
    },
    "!": {
      "icon": "info",
      "foreground": "#00CED1",
      "background": "#002020",
      "type": "text"
    }
  },
  "todo-tree.highlights.useColourScheme": true,
  "todo-tree.highlights.defaultHighlight": {
    "foreground": "#FFFFFF",
    "background": "#000000",
    "type": "text"
  },
  "autoDocstring.includeExtendedSummary": true,
  "autoDocstring.includeName": true,
  "autoDocstring.startOnNewLine": true,
  "workbench.editor.alwaysShowEditorActions": true,
  "workbench.editor.enablePreview": false,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "javascript.updateImportsOnFileMove.enabled": "always",
  "liveServer.settings.donotShowInfoMsg": true,
  "vscode-office.editorTheme": "One Dark",
  "database-client.autoSync": true,
  "liveServer.settings.donotVerifyTags": true //permite que abram varias abas uma ao lado da outra

    "terminal.integrated.defaultProfile.windows": "Command Prompt", //define qual terminal será aberto por padrão no Windows.
  "terminal.integrated.profiles.windows": {
    /*define os terminais disponíveis, com caminhos para garantir compatibilidade em diferentes arquiteturas (32/64 bits).*/
    "Command Prompt": {
      "path": [
        "${env:windir}\\Sysnative\\cmd.exe",
        "${env:windir}\\System32\\cmd.exe"
      ]
    }
  }
}

