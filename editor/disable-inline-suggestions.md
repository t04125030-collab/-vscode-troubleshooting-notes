# Disable Inline Suggestions in VS Code

## Problem

Visual Studio Code may display inline code suggestions while typing. These suggestions can be distracting when you prefer to write code manually.

## Solution

1. Open Visual Studio Code.
2. Press `Ctrl + Shift + P` to open the Command Palette.
3. Search for `Preferences: Open User Settings (JSON)`.
4. Open the settings file.
5. Add the following setting inside the existing JSON object.

{
    "editor.inlineSuggest.enabled": false,
    "editor.quickSuggestions": {
        "other": "off",
        "comments": "off",
        "strings": "off"
    },
    "editor.suggestOnTriggerCharacters": false,
    "editor.wordBasedSuggestions": "off",
    "editor.parameterHints.enabled": false,
    "editor.acceptSuggestionOnEnter": "off",
    "editor.suggest.preview": false,
    "editor.inlineSuggest.showToolbar": "never"
}

If the file already contains other settings, add this entry with the correct comma placement. Do not replace the entire settings file.

## If Suggestions Still Appear

- Check the settings of AI coding extensions.
- Check whether an extension has its own autocomplete configuration.
- Restart VS Code and test again.

## Expected Result

Inline suggestions controlled by this setting should be disabled. Other autocomplete features may require separate configuration.

---

*Documented for quick reference.*
