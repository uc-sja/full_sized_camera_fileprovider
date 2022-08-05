# Capturing full sized images using fileprovider

This is a demo project to explain the use case capturing full sized camera photos and not just the thumnail.

We will create and store a file on the device and then pass it’s URI to the default camera application via intent.
Now after clicking a picture, the camera app will then process the file internally, and save a full-size photo into it.


![](https://github.com/uc-sja/full_sized_camera_fileprovider/blob/master/app/src/main/res/drawable/ezgif.com-gif-maker.gif)


## Android Project Architecture
This is example of android project architecture.


 * [Project Setup](#project-setup)
 * [Package Module](#package-module)
 * [Naming Convention](#naming-convention)
 * [Project Module](#project-module)
 * [Project Architecture](#project-architecture)
   *  [Android SDK](#android-sdk)
   *  [Network API](network-api)
   *  [Project Module](project-module)

 * [License](#license)




# Project Setup
 * Project name - Fileprovider camera sample
 * Package name - com.example.fileprovidercamerasample
 * Package Init - Module

Dependency
AndroidX Core
Kotlin-Stdlib

