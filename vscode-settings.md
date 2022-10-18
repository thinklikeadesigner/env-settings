``` json
{
  "files.associations": {
    "*.html.erb": "erb"
  },
  "clockify.apiKey": "Xyc0nkkHCkGKigEm",
  "liveServer.settings.donotShowInfoMsg": true,
  "editor.minimap.enabled": false,
  "vim.insertModeKeyBindings": [
    {
      "before": ["k", "j"],
      "after": ["<esc>"]
    }
  ],
  "[javascript]": {
    "editor.defaultFormatter": "bysabi.prettier-vscode-standard"
  },
  "javascript.updateImportsOnFileMove.enabled": "always",
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "emmet.includeLanguages": {
    "javascript": "javascriptreact",
    "erb": "html",
    "ruby": "html"
  },
  "[dart]": {
    "editor.formatOnSave": true,
    "editor.formatOnType": true,
    "editor.rulers": [80],
    "editor.selectionHighlight": false,
    "editor.suggest.snippetsPreventQuickSuggestions": false,
    "editor.suggestSelection": "first",
    "editor.tabCompletion": "onlySnippets",
    "editor.wordBasedSuggestions": false
  },
  "todo-tree.tree.showScanModeButton": false,
  "todo-tree.highlights.useColourScheme": true,
  "todo-tree.general.tags": [
    "[ ]",
    "[x]",
    "URGENT",
    "FIXME",
    "TEST",
    "MAKEME",
    "BUG",
    "DUE",
    "UNPLUGGED",
    "WTF",
    "COMPLETE",
    "GOOGLE",
    "PENDING",
    "FUTURE",
    "NEED",
    "IDEA",
    "SPECS",
    "QUESTION",
    "NOTE",
    "REFACTOR",
    "DEAD"
  ],
  "todo-tree.regex.regex": "(//|#|<!--|;|/\\*|^|^\\s*(-|\\d+.))\\s*($TAGS)",
  "todo-tree.highlights.customHighlight": {
    "PENDING": {
      "icon": "clock",
      "foreground": "#ffffff20",
      "background": "#ffffff00",
      "iconColour": "#C6F",
      "gutterIcon": true
    },
    "WTF": {
      "icon": "hubot",
      "foreground": "#ffffff20",
      "background": "#ffffff00",
      "iconColour": "#00bfff",
      "gutterIcon": true
    },
    "GOOGLE": {
      "icon": "telescope",
      "foreground": "#ffffff20",
      "background": "#ffffff00",
      "iconColour": "#00bfff",
      "gutterIcon": true
    },
    "NEED": {
      "icon": "lock",
      "foreground": "#ffffff20",
      "background": "#ffffff00",
      "iconColour": "#00bfff",
      "gutterIcon": true
    },
    "SPECS": {
      "icon": "clippy",
      "foreground": "#ffffff20",
      "background": "#ffffff00",
      "iconColour": "#00ced1",
      "gutterIcon": true
    },
    "FUTURE": {
      "icon": "eye",
      "foreground": "#ffffff20",
      "background": "#ffffff00",
      "iconColour": "#C6F",
      "gutterIcon": true
    },
    "QUESTION": {
      "icon": "question",
      "foreground": "#ffffff20",
      "background": "#ffffff00",
      "iconColour": "#C6F",
      "gutterIcon": true
    },

    "TEST": {
      "icon": "beaker",
      "foreground": "#ffffff20",
      "background": "#ffffff00",
      "iconColour": "#00D364",
      "gutterIcon": true
    },
    "MAKEME": {
      "icon": "plus-circle",
      "foreground": "#ffffff20",
      "background": "#ffffff00",
      "iconColour": "#00ced1",
      "gutterIcon": true
    },
    "REFACTOR": {
      "foreground": "#ffffff20",
      "background": "#ffffff00",
      "icon": "sync",
      // "foreground": "#00bfff",
      "iconColour": "#00bfff",
      "gutterIcon": true
    },
    "IDEA": {
      "foreground": "#ffffff20",
      "background": "#ffffff00",
      "icon": "light-bulb",
      // "foreground": "#00bfff",
      "iconColour": "#FC6",
      "gutterIcon": true
    },
    "UNPLUGGED": {
      "foreground": "#ffffff20",
      "background": "#ffffff00",
      "icon": "plug",
      // "foreground": "#00bfff",
      "iconColour": "#00bfff",
      "gutterIcon": true
    },
    "NOTE": {
      "foreground": "#ffffff20",
      "background": "#ffffff00",
      "icon": "pencil",
      // "foreground": "#00bfff",
      "iconColour": "#00bfff",
      "gutterIcon": true
    },

    "URGENT": {
      "foreground": "#ffffff20",
      "iconColour": "#f39",
      "gutterIcon": true,
      "background": "#ffffff00",
      "icon": "alert"
    },
    "FIXME": {
      "foreground": "#ffffff20",
      "iconColour": "white",
      "gutterIcon": true,
      "background": "#ffffff00",
      "icon": "tools"
    },
    "DEAD": {
      "foreground": "#ffffff20",
      "iconColour": "#ffffff10",
      "gutterIcon": true,
      "background": "#ffffff00",
      "icon": "trash"
    },
    "COMPLETE": {
      "foreground": "#ffffff20",
      "iconColour": "#00D364",
      "gutterIcon": true,
      "background": "#ffffff00",
      "icon": "rocket"
    },
    "BUG": {
      "foreground": "#ffffff20",
      "iconColour": "#FC6",
      "gutterIcon": true,
      "background": "#ffffff00",
      "icon": "bug"
    },
    "DUE": {
      "foreground": "#ffffff20",
      "iconColour": "#FC6",
      "gutterIcon": true,
      "background": "#ffffff00"
    },
    "[ ]": {
      "foreground": "#f39",
      "iconColour": "#f39",
      "background": "#ffffff00",
      "icon": "circle"
      //   "gutterIcon": true
    },
    "[x]": {
      "background": "#ffffff00",
      "foreground": "#f39",
      "iconColour": "#f39",
      "icon": "check-circle-fill"
      //   "gutterIcon": true
    }
  },
  "eslint.options": {
    "extensions": [".js", ".jsx", ".md", ".mdx", ".ts", ".tsx"]
  },
  "eslint.validate": [
    "markdown",
    "mdx",
    "javascript",
    "javascriptreact",
    "typescript",
    "typescriptreact"
  ],
  "dart.debugExternalLibraries": true,
  "dart.debugSdkLibraries": true,
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "gitlens.hovers.currentLine.over": "line",
  "editor.suggestSelection": "first",
  "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "workbench.editorAssociations": {
    "*.ipynb": "jupyter.notebook.ipynb"
  },
  "editor.fontFamily": "'Fira Code', Monaco, 'Courier New', monospace",
  "editor.fontSize": 13,
  "editor.fontWeight": "300",
  "editor.letterSpacing": 1.2,
  "editor.lineHeight": 22,
  "editor.fontLigatures": true,
  "workbench.colorCustomizations": {},
  "prettier.jsxSingleQuote": false,
  "editor.largeFileOptimizations": false,
  "eslint.format.enable": true,
  "eslint.debug": true,
  "eslint.probe": [
    "javascript",
    "javascriptreact",
    "typescript",
    "typescriptreact",
    "html",
    "vue",
    "markdown",
    "react"
  ],
  "javascript.preferences.quoteStyle": "double",
  "prettier.singleQuote": false,
  "typescript.preferences.quoteStyle": "double",
  "javascript.format.enable": false,
  "prettier.useEditorConfig": false,
  "editor.defaultFormatter": "bung87.rails",
  "sonarlint.rules": {
    "javascript:S1871": {
      "level": "off"
    },
    "javascript:S1134": {
      "level": "off"
    },
    "javascript:S4138": {
      "level": "off"
    },
    "javascript:S3776": {
      "level": "off"
    },
    "javascript:S1763": {
      "level": "off"
    },
    "javascript:S125": {
      "level": "off"
    },
    "javascript:S905": {
      "level": "off"
    }
  },
  "terminal.integrated.tabs.enabled": true,
  "react-native.packager.port": 19000,
  "terminal.explorerKind": "external",
  "terminal.integrated.defaultProfile.osx": "/bin/zsh (migrated)",
  "material-ui-snippets.showNotesOnStartup": false,
  "files.exclude": {
    "**/.classpath": true,
    "**/.project": true,
    "**/.settings": true,
    "**/.factorypath": true
  },
  "codetime.statusBarInfo": "today",
  "files.eol": "\n",
  "prettier.requireConfig": true,
  "terminal.integrated.profiles.osx": {
    "/bin/zsh (migrated)": {
      "path": "/bin/zsh",
      "args": ["-l"]
    }
  },
  "redhat.telemetry.enabled": false,
  "vetur.validation.template": false,
  "eslint.workingDirectories": [],
  "editor.formatOnSave": true,
  "editor.formatOnType": true,
  "[erb]": {
    "editor.defaultFormatter": "aliariff.vscode-erb-beautify"
  },
  "[ignore]": {
    "editor.defaultFormatter": "foxundermoon.shell-format"
  },
  "editor.lineNumbers": "relative",
  "[shellscript]": {
    "editor.defaultFormatter": "foxundermoon.shell-format"
  },
  "[dockerfile]": {
    "editor.defaultFormatter": "ms-azuretools.vscode-docker"
  },
  "[typescriptreact]": {
    "editor.defaultFormatter": "vscode.typescript-language-features"
  },
  "workbench.colorTheme": "Tinacious Design"
}
```