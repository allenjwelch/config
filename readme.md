# General Configuration Files

## Resources
* [EditorConfig.org](https://editorconfig.org/#overview)
* [VS Code Plugin](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)
* [JetBrains Plugin](https://plugins.jetbrains.com/plugin/7294-editorconfig)

## Instructions
- Install necessary plugin (additional plugin links for other editors found at _EditorConfig.org_)
- Add .editorconfig file into root projects directory.

_"When opening a file, EditorConfig plugins look for a file named .editorconfig in the directory of the opened file and in every parent directory. A search for .editorconfig files will stop if the root filepath is reached or an EditorConfig file with root=true is found."_

### Note: 
"Adding an EditorConfig file to your project or codebase does not convert existing styles to the new ones. For example, if you have indents in your file that are formatted with tabs, and you add an EditorConfig file that indents with spaces, the indent characters are not automatically converted to spaces. "