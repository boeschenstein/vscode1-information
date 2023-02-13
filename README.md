# VS Code 1.x

VS Code Information

## Useful extensions

- Spell Checker (like streetsidesoftware.code-spell-checker)
- Draw.io editor (lik ehediet.vscode-drawio)
- ESLint (dbaeumer.vscode-eslint)
- Jest Test Explorer (kavod-io.vscode-jest-test-adapter)
- Markdown Editor (like yzhang.markdown-all-in-one)
- Markdown Preview (like bierner.markdown-mermaid)
- Markdown Linter (like DavidAnson.vscode-markdownlint)
- Path Intellisense (christian-kohler.path-intellisense)
- Pettier (esbenp.prettier-vscode)
- Show Todo's (like Gruntfuggly.todo-tree)
- XML Tools (like DotJoshJohnson.xml)

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

## Links

- Sort Imports: <https://www.npmjs.com/package/@trivago/prettier-plugin-sort-imports>
