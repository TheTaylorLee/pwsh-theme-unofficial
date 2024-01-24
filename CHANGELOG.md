# Change Log

- 0.0.1
    - Initial Release
- 0.0.2
    - Added an Extension Icon
- 0.0.3
    - Updated the theme name
- 0.0.4
    - Added the change log
- 0.0.5
    - Added PowerShell specific token colorization
    ```json
    {
        {
        "name": "pwsh variable sign",
        "scope": "punctuation.definition.variable.powershell",
        "settings": {
            "foreground": "#ffffff"
        }
    },
    {
        "name": "pwsh constant",
        "scope": "constant.language.powershell",
        "settings": {
            "foreground": "#ffc847"
        }
    },
     ```
- 0.0.6
    - Updated preview image and readme
- 0.0.7
    - Update status bar color when no folder is selected.
    - Update editor scrollbar transparency so code is not visible opposite the minimap. Scrollbar informational markers are now more easily seen.
    ```json
    //old
    "statusbar.noFolderBackground": "#eeeeee",
    "editorOverviewRuler.background": "#ff000000"
    //new
    "statusbar.noFolderBackground": "#191919",
    "editorOverviewRuler.background": "#191919"
    ```
- 0.0.8
    - Update package readme
- 0.0.9
    - Remove duplicate statusbar.noFolderBackground entry
- 1.0.0
    - Remove bracketmatch tokenization so the cursor can be located.
    ```json
    //old
	"editorBracketMatch.background": "#91e5ff2a",
	"editorBracketMatch.border": "#00ff34"
    //new
    "editorBracketMatch.background": "#91e5ff00",
	"editorBracketMatch.border": "#00ff3400"
    ```
- 1.1.0
    - Small readme changes.
    - Update some highlighting and selection tokens to better stand out.
    ```json
    //old
    "editor.selectionBackground": "#4b4b4b74",
    "editor.findMatchBackground": "#5b6c82",
    "editor.findMatchHighlightBackground": "#58ffe85a",
	"editor.rangeHighlightBorder": "#eeeeee00",
	"editor.hoverHighlightBackground": "#264f7840"
    //new
    "editor.selectionBackground": "#004972b8",
    "editor.findMatchBackground": "#004972b8",
    "editor.findMatchHighlightBackground": "#004972b8",
    "editor.rangeHighlightBorder": "#91e5ff",
    "editor.hoverHighlightBackground": "#004972b8"
    ```
- 1.2.0
    - Update Readme
- 1.2.1
    - Update Readme
- 1.2.2
    - Update Readme
- 2.0.0
    - Added a Light Mode
- 2.0.1
    - Update Readme
- 3.0.0
    - Added Pwsh Darker theme
- 3.0.1
    - Update Readme
- 3.1.0
    - Update Pwsh Darker
    ```json
    //old
    "editor.foldBackground": "#388c8c",
    "editor.findMatchBackground": "#004972b8",
    "editor.findMatchHighlightBackground": "#004972b8",
    //new
    "editor.foldBackground": "#2d1e7e",
    "editor.findMatchBackground": "#971010",
    "editor.findMatchHighlightBackground": "#5c1e1e",
    ```