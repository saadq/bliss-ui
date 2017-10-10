# bliss-ui
Ultra-minimalist theme optimized for ES6+ JavaScript.

![Bliss UI](https://i.imgur.com/25VF7AU.png)

### Installation

```
$ apm install bliss-ui
```

### Setup
1. Go to your `Preferences` and click on `Themes` in the sidebar.
2. Click on the `Syntax Theme` dropdown and change the value to `Bliss`.

### Customise Styles

#### Hide title bar
It is recommended to hide the title bar by using this setting in your `"core": { ... }` config.

```json
"titleBar": "hidden"
```

#### Disable Git highlighting
To disable Git highlighting from the tree view, you can add the following lines in your stylesheet:

```less
.icon {
    color: #c0c5ce;
}
```

### Related Projects
* [Bliss Syntax](https://github.com/saadq/bliss-syntax) – A syntax theme that matches this UI theme.
* [Termination](https://github.com/Fred-Barclay/Termination) – An integrated terminal for Atom. It comes with many different themes that you can configure in the settings, including a Bliss theme.
* [Hyper Material Spacegray](https://github.com/saadq/hyperterm-material-spacegray) – A matching theme for the [Hyper](https://hyper.is) terminal.

### Credits
This theme is a fork of the awesome [apex-ui](https://github.com/apex/apex-ui) theme created by [TJ Holowaychuk](https://github.com/tj).

### License
MIT
