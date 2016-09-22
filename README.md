Cordova PouchDB hello world app, with SQLite Plugin
=====

### Changes from original project
    PouchDB 3.3.1 to PouchDB 6
    Whitelist updated in config.xml
    This example assume you have a CouchDB server running on 192.168.0.108

This is a basic Cordova app. It was created using the `cordova` CLI, by running:

    cordova create pouchdb-hello-world

Then I installed the [SQLite Plugin](https://github.com/brodysoft/Cordova-SQLitePlugin) by running:

    cordova plugin add https://github.com/brodysoft/Cordova-SQLitePlugin

To run the app yourself on a variety of platforms, just check out the code and follow the instructions below.

### Android

    cordova platform add android
    cordova run android
    
What you'll see:

<a href="./screenshots/android.png"><img src="./screenshots/android.png" height=500/></a>

### iOS

    cordova platform add ios
    cordova run ios

What you'll see:

<a href="./screenshots/ios.png"><img src="./screenshots/ios.png" height=500/></a>

### FirefoxOS

    cordova platform add firefoxos
    cordova build firefoxos

(Then install manually using `about:app-manager` in Firefox.)

What you'll see:

<a href="./screenshots/firefoxos.png"><img src="./screenshots/firefoxos.png" height=500/></a>

### Other platforms

Feel free to try it out and take screenshots. :)
