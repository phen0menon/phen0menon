1. Install APC extension: https://marketplace.visualstudio.com/items?itemName=drcika.apc-extension
2. Put `custom-css-vscode.css` file into a desire directory
3. In the `settings.json` update `"apc.imports"` in accordance with your directories:
    ```
    "apc.imports": [
      "file:///Users/User/Development/config/custom-js-vscode.js",
      "file:///Users/User/Development/config/custom-css-vscode.css"
    ],
    ```
4. Open VS Code, Cmd + Shift + P -> Enable APC Extension -> Restart
5. Enjoy