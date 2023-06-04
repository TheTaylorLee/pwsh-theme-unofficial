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
- 0.0.10
    - Remove bracketmatch tokenization so the cursor can be located.
    ```json
    //old
	"editorBracketMatch.background": "#91e5ff2a",
	"editorBracketMatch.border": "#00ff34"
    //new
    "editorBracketMatch.background": "#91e5ff00",
	"editorBracketMatch.border": "#00ff3400"
    ```