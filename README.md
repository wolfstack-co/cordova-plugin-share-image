cordova-plugin-share-image
====================

Cordova Plugin to open native "share" popup in Android and iOS

### Install

In your phonegap/cordova project, type:

`cordova plugins add https://github.com/wolfstack-co/cordova-plugin-share-image.git`

### Usage

`navigator.share(text,title,mimetype)`

* text: Base64 string of image to share, i.e. "Incredible plugin"
* title: Title of popup, i.e. "Share this quote" (android only, default: "Share")
* mimetype: Mimetype, i.e. "image/png"

### License

MIT license

