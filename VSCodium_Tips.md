## Switch focus between editor and integrated terminal

### Open the keybindings.json from the editor: CMD-SHIFT-P -> Preferences: Open Keyboard Shortcuts File and add these entries:

```javascript
// Toggle between terminal and editor focus
{ "key": "ctrl+`", "command": "workbench.action.terminal.focus"},
{ "key": "ctrl+`", "command": "workbench.action.focusActiveEditorGroup", "when": "terminalFocus"}
```
