```bash
# Install Monaca CLI - Onsen UI toolkit
$ npm install -g monaca
# Choose React template
$ monaca create helloworld
# Run preview, or "monaca debug" to run on your device
$ cd helloworld; monaca preview
```

```bash
$ monaca create react-onsen-xxx
? Choose a category: Onsen UI and React
? Select a template - Press P to see a preview (Use arrow keys: ↑ ↓ ← →)
> Onsen UI V2 React Tabbar
  Onsen UI V2 React Splitter
  Onsen UI V2 React Navigation
  Onsen UI V2 React Minimum

Type "cd react-onsen-xxx" and run monaca command again.
  > monaca preview      => Run app in the browser
  > monaca debug        => Run app in the device using Monaca Debugger
  > monaca remote build => Start remote build for iOS/Android/Windows
  > monaca upload       => Upload this project to Monaca Cloud IDE
```

```bash
# The "react-onsenui" library requires the "onsenui" library.
$ npm install --save-dev onsenui react-onsenui
```
