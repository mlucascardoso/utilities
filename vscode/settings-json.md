# Settings JSON configs

```json
{
    // ###### EDITOR ######
    "editor.codeActionsOnSave": { "source.fixAll.eslint": true },
    "editor.cursorBlinking": "expand",
    "editor.detectIndentation": false,
    "editor.fontFamily": "'Droid Sans Mono', 'monospace', monospace, 'Droid Sans Fallback'",
    "editor.fontLigatures": true,
    "editor.fontSize": 12,
    "editor.lineHeight": 26,
    "editor.minimap.enabled": false,

    "emmet.includeLanguages": { "javascript": "javascriptreact" },
    "emmet.syntaxProfiles": { "javascript": "jsx" },

    // ###### EXPLORER ######
    "explorer.confirmDelete": false,
    "explorer.compactFolders": false,

    // ###### LANGUAGES ######
    "[css]": {
        "editor.formatOnPaste": true,
        "editor.formatOnSave": true
    },
    "[javascript]": {
        "editor.formatOnPaste": true,
        "editor.formatOnSave": true
    },
    "[typescript]": {
        "editor.formatOnPaste": true,
        "editor.formatOnSave": true
    },
    "[typescriptreact]": {
        "editor.formatOnPaste": true,
        "editor.formatOnSave": true
    },
    "typescript.updateImportsOnFileMove.enabled": "always",

    // ###### FILES ASSOCIATIONS ######
    "files.associations": {
        ".sequelizerc": "javascript",
        "*.hdbprocedure": "sql",
        "*.xsjs": "javascript"
    },

    "material-icon-theme.folders.associations": { "migrations": "tools"},

    // ###### WORKBENCH ######
    "workbench.colorTheme": "Dracula",
    "workbench.iconTheme": "material-icon-theme"
}
```