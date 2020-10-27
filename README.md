<h1 align="center">
   Pedro's Choice - Keymap
</h1>

This extension imports a selection of keybindings chosen by Pedro.

## FAQ
### What keyboard shortcuts are included?


|key                       | command            |
|--------------------------|--------------------|
|ctrl+shift+c              |editor.action.commentLine|
|ctrl+e                    |editor.action.deleteLines|
|ctrl+down           |editor.action.copyLinesDownAction|
|ctrl+up             |editor.action.copyLinesUpAction|
|alt+down            |editor.action.moveLinesDownAction|
|alt+up              |editor.action.moveLinesUpAction|
|ctrl+shift+up         |editor.action.insertCursorAbove|
|ctrl+shift+down       |editor.action.insertCursorBelow|
|ctrl+1                    |workbench.view.explorer|
|ctrl+shift+1              |workbench.files.action.focusOpenEditorsView|
|alt+u                  |editor.action.transformToUppercase|
|alt+l                  |editor.action.transformToLowercase|
|ctrl+shift+numpad_add     |editor.unfoldAll|
|ctrl+shift+numpad_subtract|editor.foldAll|
|ctrl+shift+w              |workbench.action.closeEditorsInGroup|


## Contributing
### How do I contribute a keyboard shortcut?

I may have missed an important keyboard shortcut or you may have a sugestion.


1. Head over to the [GitHub repository](https://github.com/pedrozocatelli/vscode-pedros-choice-keybinding). 
2. Open the [`package.json` file](https://github.com/pedrozocatelli/vscode-pedros-choice-keybinding/blob/main/package.json). 
3. Add a JSON object to [`contributes.keybindings`](https://github.com/pedrozocatelli/vscode-pedros-choice-keybinding/blob/main/package.json#L26) as seen below. 
4. Open a pull request. 

```json
{
   "key": "<key combination for the shortcut>",
   "command": "<which command it will trigger>",
   "when": "<when it should trigger>"
}
```

## License
[MIT](LICENSE.md)