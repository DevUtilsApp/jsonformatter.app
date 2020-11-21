# JSON Formatter/Validator
Format and validate a JSON string without online tools. [DevUtils.app](https://devutils.app) allows you to quickly format and validate a JSON string without any internet connection. It supports various formats (2 spaces, 4 spaces, tabs) and can also minify your JSON if needed.

<p align="center">
  <img src="https://devutils.app/assets/json-formatter-validator-dark.png" alt="DevUtils.app: JSON Formatter/Validator macOS app"/>
  <br/>
  <a href="https://devutils.app/">🚀  Download</a> | <a href="https://devutils.app/demo">🎬  Demo & Screenshots</a> | <a href="https://github.com/DevUtilsApp/DevUtils-app">📝  View source</a>
</p>

## Quickly format JSON strings
You can format your JSON strings from anywhere in your macOS (terminal, in email, web browser,...).DevUtils will inspect your clipboard content and automatically select the JSON Formatter/Validator tool if the content is a valid JSON. Activate the app by:

* Copy text ► Press ⌃⌥⌘Space `(Or your own customized hotkey, up to you)`
* Copy text ► Click to icon <img src="https://devutils.app/menu-icon-dark.png" alt="DevUtils.app status bar icon" width="28px" /> in the status bar
* Select text ► Right-click ► "Inspect in DevUtils.app" `(This menu appears after you install the app)`

## Input
Enter your JSON string in the left panel of the tool. The formatted JSON will be rendered in the right panel.

If you already have the JSON string in your clipboard, click the "Clipboard" button will automatically use the clipboard's content.

Select the format you want in the select box in the top right corner. The currently supported formats are:

- 2 spaces
- 4 spaces
- 1 tab
- Minified

## Output

The formatted JSON string will be rendered and highlighted in the right panel.

If your JSON string has syntax errors, the errors will be highlighted in red background and listed at the bottom of the screen.

Click each error line to highlight the syntax error from your input.

<img src="https://devutils.app/assets/settings/json-formatter-syntax-error.png" alt="DevUtils.app: JSON Formatter/Validator macOS app"/>

## Options
When you activate the app, DevUtils will inspect your clipboard content and automatically select the JSON Formatter/Validator tool if the content is a valid JSON. You can disable this automatic feature by unticking the option in the setting panel (the gear icon).

You can also configure the tool to allow trailing commas and comments in your JSON. Some people find this useful when working with JSON and JavaScript.

<img src="https://devutils.app/assets/settings/setting-json-formatter.png" alt="DevUtils.app: JSON Formatter/Validator macOS app"/>
