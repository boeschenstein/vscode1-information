# VS Code 1.x

VS Code Information

## Prepare Plugin recommendation:

Add the file `\Frontend\.vscode\extensions.json`:

```json
{
  "recommendations": [
    "angular.ng-template",
    "johnpapa.angular2",
    "natewallace.angular2-inline",
    "steoates.autoimport",
    "christian-kohler.path-intellisense",
    "esbenp.prettier-vscode",
    "gruntfuggly.todo-tree",
    "ms-vscode.vscode-typescript-tslint-plugin",
    "gruntfuggly.todo-tree",
    "streetsidesoftware.code-spell-checker"
  ]
}
```

## Config for VS Code

Add the file `\Frontend\.vscode\settings.json`:

```json
{
  "extensions.ignoreRecommendations": false,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.formatOnSave": true,
  "prettier.requireConfig": true,
  "editor.codeActionsOnSave": {
    "source.organizeImports": true
  },
  "todo-tree.tree.showScanModeButton": false,
  "todo-tree.highlights.enabled": true,
  "todo-tree.general.tags": [
    "BUG",
    "HACK",
    "FIXME",
    "TODO",
    "XXX",
    "todo",
    "hack",
    "fixme",
    "bug",
    "xxx",
    "Todo",
    "ToDo",
    "Hack",
    "Fixme",
    "FixMe",
    "Bug"
  ],
  "cSpell.words": [
    "fontawesome",
    "fortawesome",
    "memoized",
    "ngrx",
    "runstate",
    "signalr",
    "ssis",
    "upsert"
  ]
}
```
