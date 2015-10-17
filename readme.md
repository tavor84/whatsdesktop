# <img src="media/logo-symbol.png" width="45" align="left">&nbsp;WhatsDesktop

> Unofficial WhatsApp app

<br>
[![](media/screenshot.png)](https://github.com/mawie81/whatsdesktop/releases/latest)

*Requires OS X 10.8+ or Linux. Windows support planned.*

## Install

### OS X

#### Manually

[**Download**](https://github.com/mawie81/whatsdesktop/releases/latest), unzip, and move `WhatsDesktop.app` to the `/Applications` directory.

### Linux

[**Download**](https://github.com/mawie81/whatsdesktop/releases/latest) and unzip to some location.

To add a shortcut to the app, create a file in `~/.local/share/applications` called `whatsdesktop.desktop` with the following contents:

```
[Desktop Entry]
Name=WhatsDesktop
Exec=/full/path/to/folder/whatsdesktop
Terminal=false
Type=Application
Icon=/full/path/to/folder/WhatsDesktop/resources/app/media/logo-symbol.png
```

## Dev

Built with [Electron](http://electron.atom.io).

###### Commands

- Init: `$ npm install`
- Run: `$ npm start`
- Build OS X: `$ npm run build-osx`
- Build Linux: `$ npm run build-linux`
- Build all: `$ npm run build` *(OS X only)*


## License

MIT © [Marcel Wiehle](http://marcel.wiehle.me)
