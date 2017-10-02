# Visual Studio Code Customization

## 1. Extensions

- [Browsersync][browser-sync]

    ![Browsersync][browser-sync-image]

- [HTML Snippets][html-snippets]

    ![HTML Snippets][html-snippets-image]

- [One Dark Pro][one-dark-pro]

    ![One Dark Pro][one-dark-pro-image]

- [Power Mode][power-mode]

    ![Power Mode][power-mode-image]

- [Path Intellisense][path-intellisense]

    ![Path Intellisense][path-intellisense-image]

## 2. Settings

  ```js
  {
    "workbench.colorTheme": "One Dark Pro Vivid",
    "files.autoSave": "afterDelay",
    "files.autoSaveDelay": 500,
    "editor.tabSize": 2,
    "powermode.enabled": true,
    "powermode.shakeIntensity": 1,
    "powermode.explosionFrequency": 3,
    "powermode.explosionDuration": 500,
    "workbench.iconTheme": "simple-icons"
  }
  ```

## 3. NPM

1. _DevDependencies_

    npm i --D @types/angular  // to add angular 1.6.32 intellisense

[browser-sync]: https://marketplace.visualstudio.com/items?itemName=jeremyrajan.browsersync
[html-snippets]: https://marketplace.visualstudio.com/items?itemName=abusaidm.html-snippets
[one-dark-pro]: https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.Material-theme
[power-mode]: https://marketplace.visualstudio.com/items?itemName=hoovercj.vscode-power-mode
[path-intellisense]: https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense

[browser-sync-image]: https://user-images.githubusercontent.com/2890683/30096048-d4046ff6-9308-11e7-85f0-5aae0bedc29a.png "Browser Sync"
[html-snippets-image]: https://i.imgur.com/VOhBvHb.gif "HTML Snippets"
[one-dark-pro-image]: https://raw.githubusercontent.com/Binaryify/OneDark-Pro/master/static/screenshot1.png "One Dark Pro"
[power-mode-image]: https://github.com/hoovercj/vscode-power-mode/raw/master/images/demo-presets-particles.gif "Power Mode"
[path-intellisense-image]: https://i.giphy.com/iaHeUiDeTUZuo.gif "Path Intellisense"