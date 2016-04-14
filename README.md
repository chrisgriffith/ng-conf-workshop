# Up and Running with Ionic v2

## ng-conf 2016

For those attending my workshop on the Fair Day at this year's ng-conf, we will need to install a few things to help maxmimize the session.

1) If you do not have nodejs installed, please do so. It can downloaded from http://nodejs.org/. I recommend using 4.4.3

2) If you do not have Git installed, you will need to do so as well. It can be downloaded from http://git-scm.com/. The Ionic CLI uses it to manage installations of components. For Windows users, make sure you install GIT Bash as well, as it mirrors the Unix Bash system.

3) To install the Ionic SDK and create Ionic 2 projects, you’ll need to install the latest beta release: 
```npm install -g ionic@beta```

    Note: Macintosh users may have to prepend sudo before the npm install command.

4) We will need to install the Cordova CLI. ```npm install -g cordova```

5) Install the free Ionic View app on your mobile device. 

   iOS: https://itunes.apple.com/us/app/ionic-view/id849930087?ls=1&mt=8

   Android: https://play.google.com/store/apps/details?id=com.ionic.viewapp

6) Get an account at https://apps.ionic.io/signup. We will use this service  test our app on device.

This is the bare minimum for Ionic development. If you are planing on deploying your apps on your device you will need to do some additional installed based on the platform you are targeting.

You will also need Google Chrome and your favorite IDE. I am a fan of Visual Studio Code (https://code.visualstudio.com/). Make sure you also grab the Cordova Tools (https://marketplace.visualstudio.com/items?itemName=vsmobile.cordova-tools). 

## Optional Installations
Although we will not be deploying to actual device, you might wish to explore that capability post-workshop. Here are the instructions to do so.


## iOS
---
For iOS development, several additional items need to be installed. These instructions are for Macintosh users only. 

First, install XCode (https://developer.apple.com/xcode/) and the iOS SDK. 

There are two more npm packages that we need to install

1) ```npm install -g ios-sim```. This module will allow us to launch the iOS Simulator directly from the command line.

2) ```npm install -g ios-deploy```. This module will allow us to install and launch our apps on properly configured iOS devices.

For more information see: http://docs.phonegap.com/en/edge/guide_platforms_ios_index.md.html

To directly install your apps on your device you will need to become an Apple Developer ($99 per year).

## Android
---
For Android development, you’ll need to install the Android SDK (http://developer.android.com/sdk/index.html). The Android SDK allows you to build compile to a target device running Android. Although the Android SDK comes with a stock emulator, Genymotion is recommended, since it’s much faster (https://www.genymotion.com/).

But before we install that, we need to install the Java Developer Kit version 6 or later. (http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)

Select the option for your platform. We just need the JDK, so you can ignore the other options here.

Once that is done installing, we will need to modify the PATH environment variable. This will vary depending on your platform.

For more information see: http://docs.phonegap.com/en/edge/guide_platforms_android_index.md.html 
