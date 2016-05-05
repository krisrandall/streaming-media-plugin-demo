# streaming-media-plugin-demo
Really Simple Cordova Video Example
This repo is a really simple example of the [Cordova Streaming Media Plugin (KMOD version)](https://github.com/krisrandall/Streaming-Media-Cordova-Plugin/)

## Requirements ##
* Cordova 

## Install Instructions ##
* `$ git clone https://github.com/krisrandall/Streaming-Media-Cordova-Plugin.git # get the plugin locally`
* `$ cordova create streaming-media-plugin-demo # create a cordova app`
* `$ cd streaming-media-plugin-demo/`
* `$ cordova platform add ios android`
* `$ cordova plugin add ../Streaming-Media-Cordova-Plugin/ # add local version of plugin to app`
* `$ cd www`
* `$ git clone https://github.com/krisrandall/streaming-media-plugin-demo.git # get the source from this repo `
* `$ cp streaming-media-plugin-demo/index.html . # and add it into your app `
* `$ cd ..`
* `$ cordova build`

