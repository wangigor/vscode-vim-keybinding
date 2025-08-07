# VSCode Vim Keybindings

This is a set of custom keybindings for VSCode with the Vim extension, designed to improve navigation and workflow efficiency.

## Installation

1.  Open VSCode.
2.  Go to `File > Preferences > Keyboard Shortcuts` or use the shortcut `Cmd+K Cmd+S`.
3.  Click on the `Open Keyboard Shortcuts (JSON)` button in the top right corner.
4.  Copy the contents of the `keybindings.json` file in this repository and paste them into your `keybindings.json` file.

## Keybindings

### Navigation

| Keybinding | Command | Description |
| :--- | :--- | :--- |
| `Ctrl+h` | `workbench.action.navigateLeft` | Navigate to the editor group on the left. |
| `Ctrl+l` | `workbench.action.navigateRight` | Navigate to the editor group on the right. |
| `Ctrl+j` | `workbench.action.navigateUp` | Navigate to the editor group above. |
| `Ctrl+k` | `workbench.action.navigateDown` | Navigate to the editor group below. |
| `Space` `,` | `workbench.action.showAllEditors` | Show a list of all open editors. |
| `Space` `e` | `runCommands` | Toggle sidebar visibility and focus the file explorer or editor. |
| `s` `h` | `workbench.action.splitEditor` | Split the current editor horizontally. |
| `s` `v` | `workbench.action.splitEditorDown` | Split the current editor vertically. |
| `Shift+H` | `workbench.action.navigateBack` | Go back in navigation history. |
| `Shift+L` | `workbench.action.navigateForward` | Go forward in navigation history. |

### Coding

| Keybinding | Command | Description |
| :--- | :--- | :--- |
| `Space` `c` `a` | `editor.action.codeAction` | Show available code actions (quick fix). |
| `Shift+K` | `editor.action.moveLinesUpAction` | (Visual Line Mode) Move selected lines up. |
| `Shift+J` | `editor.action.moveLinesDownAction` | (Visual Line Mode) Move selected lines down. |
| `Shift+K` | `editor.action.showHover` | (Normal Mode) Show hover information for the symbol under the cursor. |
| `Space` `Space` | `workbench.action.quickOpen` | Open the "Go to File..." dialog. |
| `Space` `g` `d` | `editor.action.revealDefinition` | Go to the definition of the symbol under the cursor. |
| `Space` `g` `r` | `editor.action.goToReferences` | Show all references to the symbol under the cursor. |
| `Space` `g` `i` | `editor.action.goToImplementation` | Go to the implementation of the symbol under the cursor. |
| `f` `f` | `workbench.action.findInFiles` | Open the "Find in Files" search panel. |
| `Enter` | `search.action.focusSearchList` | (In search input) Focus the list of search results. |
| `Ctrl+n` | `editor.action.addSelectionToNextFindMatch` | Add the next occurrence of the current selection to the find match. |

### File Explorer

These commands are active when the File Explorer is focused.

| Keybinding | Command | Description |
| :--- | :--- | :--- |
| `r` | `renameFile` | Rename the selected file or folder. |
| `c` | `filesExplorer.copy` | Copy the selected file or folder. |
| `p` | `filesExplorer.paste` | Paste the copied file or folder. |
| `x` | `filesExplorer.cut` | Cut the selected file or folder. |
| `d` | `deleteFile` | Delete the selected file or folder. |
| `a` | `explorer.newFile` | Create a new file in the current directory. |
| `s` | `explorer.openToSide` | Open the selected file in a new editor to the side. |
| `Shift+S` | `runCommands` | Open the selected file in a vertical split and close all other editors. |
| `Enter` | `explorer.openAndPassFocus` | (On a file) Open the file in the current editor group. |
| `Enter` | `list.toggleExpand` | (On a folder) Expand or collapse the folder. |
