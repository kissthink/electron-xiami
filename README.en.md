<img src="assets/icon.png" alt="logo" height="80" align="right" />

# Electron Xiami

[中文说明](README.md)

A [xiami](http://www.xiami.com/) desktop application for Linux.
Supported by [Electron](https://electron.atom.io/).

![screenshot_macos](https://user-images.githubusercontent.com/13460738/34644583-38a2a2b6-f39e-11e7-8831-e21475427ccb.jpg)

![screenshot_gnome](https://user-images.githubusercontent.com/13460738/34747515-6fd6805c-f5fd-11e7-9aed-25f51c2e3b49.jpg)

![xfce_screenshot](https://user-images.githubusercontent.com/13460738/34656057-d7ec0f44-f478-11e7-8c34-6cbe78601748.jpg)

*This is not the official desktop client. It's released under open source. If you are facing any issue, please use [this link](https://github.com/eNkru/electron-xiami/issues) to report.*

## Feature
* Play Xiami online music on Linux platform.
* Close to minimise.
* Dock tray support.
* Play control in context menu
* Local configuration support
* Multi-language support

## Pre-Request
* [GIT](https://git-scm.com/)
* [NPM](https://www.npmjs.com/)

## Build & Install
Clone the repository and run in development mode.
```
git clone https://github.com/eNkru/electron-xiami.git
cd electron-xiami
npm install
npm start
```
Build the application 
```
npm run dist:linux
```

## Release
```
npm version (new release version)
git push origin master
git push origin --tags
npm publish
```

## Download
The released application can be downloaded [here](https://github.com/eNkru/electron-xiami/releases).

## License
[MIT](https://github.com/eNkru/electron-xiami/blob/master/LICENSE)
