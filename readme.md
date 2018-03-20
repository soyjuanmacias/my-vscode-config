# VS Code Config

My own VS Code config.

```json
{
  "workbench.iconTheme": "material-icon-theme",
  "gitlens.advanced.messages": {
    "suppressCommitHasNoPreviousCommitWarning": false,
    "suppressCommitNotFoundWarning": false,
    "suppressFileNotUnderSourceControlWarning": false,
    "suppressGitVersionWarning": false,
    "suppressLineUncommittedWarning": false,
    "suppressNoRepositoryWarning": false,
    "suppressUpdateNotice": false,
    "suppressWelcomeNotice": true
  },
  "atomKeymap.promptV3Features": true,
  "editor.multiCursorModifier": "ctrlCmd",
  "editor.formatOnPaste": true,
  "javascript.validate.enable": false,
  "terminal.integrated.shell.osx": "/bin/zsh",
  "workbench.panel.location": "bottom",
  "terminal.integrated.fontFamily": "DejaVu Sans Mono for Powerline",
  "window.zoomLevel": 0,
  "explorer.confirmDragAndDrop": false,
  "eslint.autoFixOnSave": true,
  "workbench.startupEditor": "newUntitledFile",
  "editor.tabSize": 2,
  "editor.detectIndentation": false,
  "files.exclude": {
    "**/.git": false,
    "**/.svn": true,
    "**/.hg": true,
    "**/CVS": true,
    "**/.DS_Store": false
  },
  "typescript.autoImportSuggestions.enabled": false,
  "workbench.editor.openPositioning": "right",
  "workbench.editor.tabCloseButton": "right",
  "material-icon-theme.hidesExplorerArrows": true,
  "material-icon-theme.activeIconPack": "react",
  "material-icon-theme.folders.theme": "specific"
}
```