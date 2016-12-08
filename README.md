# User settings for Visual Studio Code

User `settings.json` file which overrides some default settings.

Based on my opinions of what is best practice!

## Editor

`"editor.tabSize": 2`  
Two space indentation. It tends to suit the programming languages which I use most frequently.  
_Project specific config files should be used when working on projects which use a different tab size._

`"editor.rulers": [80, 120]`  
Prefer lines less than 80 characters long but always keep them less than 120.

`"editor.renderWhitespace": "all"`  
Show all whitespace characters for explicit clarity.

`"editor.acceptSuggestionOnEnter": false`  
Don't accept IntelliSense suggestions with the `Enter` key -- only accept with `Tab`.

## Diff

`"diffEditor.ignoreTrimWhitespace": false`  
Show leading and trailing whitespace changes in diffs.

## Blank Line

For the extension: Blank Line at the End of File  
https://marketplace.visualstudio.com/items?itemName=riccardoNovaglia.missinglineendoffile

Because files should always end with a blank line.

`"blankLine.showMessage": false`  
Don't show message to inform that blank line was added.
