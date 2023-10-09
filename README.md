# WebStorm New UI Theme

This theme has been designed with color schemes similar to [WebStorm New UI](https://www.jetbrains.com/help/webstorm/new-ui.html).

The syntax highlighting follows the color palette of the WebStorm New UI, but there are some parts that purposely differentiate themselves from the WebStorm theme.

For example, I've applied italic styles to built-in objects, types and interfaces, making it easier to distinguish when writing code. There are more things besides this. Also, The syntax highlighting method between the dark theme and the light theme is slightly different.

## Preview

### New Light

![Webstorm New Light](https://raw.githubusercontent.com/eenaree/webstorm-new-ui-theme/main/images/preview_new_light.png)

### New Light with Dark Header

![Webstorm New Light with Dark Header](https://raw.githubusercontent.com/eenaree/webstorm-new-ui-theme/main/images/preview_new_light_with_darkHeader.png)

### New Dark

![Webstorm New Dark](https://raw.githubusercontent.com/eenaree/webstorm-new-ui-theme/main/images/preview_new_dark.png)

### New Darcula

![Webstorm New Darcula](https://raw.githubusercontent.com/eenaree/webstorm-new-ui-theme/main/images/preview_new_darcula.png)

## Installation

1. Open **Extensions** in VSCode's sidebar. (or From Command Palette (**Ctrl+Shift+P**), `View: Show Extensions`)
2. Search for `WebStorm New UI Theme`.
3. Click **Install** to install it.
4. From Command Palette (**Ctrl+Shift+P**), select `Preferences: Color Theme` and select a theme you want.
   - `Webstorm New Light`
   - `Webstorm New Light with Dark Header`
   - `Webstorm New Dark`
   - `Webstorm New Darcula`

## Supported Languages

- JavaScript
- TypeScript
- HTML
- CSS
- Markdown
- JSON

## Recommended Editor Settings

```json
"editor.fontFamily": "'Source Code Pro SemiBold'",
"editor.inlayHints.fontSize": 12,
"editor.inlayHints.padding": true,
```

- Changing the color of the indented space uses [indent-rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow) extension.

## Resources

- [WebStorm Darcula Theme](https://marketplace.visualstudio.com/items?itemName=imekachi.webstorm-darcula)
- [Int UI Theme](https://marketplace.visualstudio.com/items?itemName=baran-wang.vscode-theme-jetbrains-new-ui)
