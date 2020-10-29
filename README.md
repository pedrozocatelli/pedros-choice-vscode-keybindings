<h1 align="center">
   Pedro's Choice - Keymap
</h1>

This extension imports a selection of the best keybindings chosen by Pedro.

## What keyboard shortcuts are included?


| Command | macOS | Windows | Linux |
| :------ | :---- | :------ | :---- |
| `closeEditorsInGroup` | `cmd+shift+w` | `ctrl+shift+w` | `ctrl+shift+w` |
| `commentLine` | `cmd+shift+c` | `ctrl+shift+c` | `ctrl+shift+c` |
| `copyLinesDownAction` | `ctrl+down` | `ctrl+down` | `ctrl+down` |
| `copyLinesUpAction` | `ctrl+up` | `ctrl+up` | `ctrl+up` |
| `cursorEndSelect` | `cmd+shift+e` | `ctrl+shift+e` | `ctrl+shift+e` |
| `cursorHomeSelect` | `cmd+shift+a` | `ctrl+shift+a` | `ctrl+shift+a` |
| `deleteLines` | `cmd+e` | `ctrl+e` | `ctrl+e` |
| `focusOpenEditorsView` | `cmd+shift+1` | `ctrl+shift+1` | `ctrl+shift+1` |
| `fold` | `cmd+numpad_subtract   ` | `ctrl+numpad_subtract` | `ctrl+numpad_subtract` |
| `foldAll` | `cmd+shift+numpad_subtract   ` | `ctrl+shift+numpad_subtract` | `ctrl+shift+numpad_subtract` |
| `insertCursorAbove` | `cmd+shift+up` | `ctrl+shift+up  ` | `ctrl+shift+up ` |
| `insertCursorBelow` | `cmd+shift+down` | `ctrl+shift+down` | `ctrl+shift+up` |
| `joinLines` | `cmd+j` | `alt+j` | `alt+j` |
| `jumpToBracket` | `cmd+m` | `ctrl+m` | `ctrl+m` |
| `moveLinesDownAction` | `cmd+down` | `alt+down` | `alt+down` |
| `moveLinesUpAction` | `cmd+up` | `alt+up` | `alt+up` |
| `transformToLowercase` | `cmd+l` | `alt+l` | `alt+l` |
| `transformToUppercase` | `cmd+u` | `alt+u` | `alt+u` |
| `unfold` | `cmd+numpad_add ` | `ctrl+numpad_add ` | `ctrl+numpad_add ` |
| `unfoldAll` | `cmd+shift+numpad_add ` | `ctrl+shift+numpad_add ` | `ctrl+shift+numpad_add ` |
| `viewExplorer` | `cmd+1` | `ctrl+1` | `ctrl+1` |



## Contributing
### How do I contribute?

If you have a sugestion of an awesome shortcut, let me know.

1. Head over to the [GitHub repository](https://github.com/pedrozocatelli/pedros-choice-vscode-keybindings). 
2. Open the [`package.json` file](https://github.com/pedrozocatelli/pedros-choice-vscode-keybindings/blob/main/package.json). 
3. Add a JSON object to [`contributes.keybindings`](https://github.com/pedrozocatelli/pedros-choice-vscode-keybindings/blob/main/package.json#L199) as seen below. 
4. Open a pull request. 

```json
{
   "mac": "<keyboard shortcut for mac>",
   "win": "<keyboard shortcut for windows>",
   "linux": "<keyboard shortcut for linux>",
   "key": "<default keyboard shorcut>",
   "command": "<which command it will trigger>",
   "when": "<when it should trigger>"
}
```

## License
[MIT](LICENSE.md)