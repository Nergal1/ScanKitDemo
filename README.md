# Scan Kit

## Table of Contents

 * [Introduction](#Introduction)
 * [Getting Started](#Getting-Started)
 * [Supported Environments](#Supported-Environments)
 * [Result](#Result)
 * [License](#License)


## Introduction
   The sample code shows how to use the HMS Scan Kit's code scanning capabilities to help developers quickly build code scanning capabilities within applications.

   Default View:         The app directly calls the scanning activity of HUAWEI Scan Kit, and obtains the scanning result through the asynchronous callback API. Barcodes can be scanned using the device camera, or through an imported image.
   Customized View:      The app directly creates a RemoteView, and obtains the scanning result through the asynchronous callback API. Barcodes can be scanned using the device camera, or through an imported image.
   Bitmap API:           The app directly passes a bitmap through the bitmap API, and obtains the scanning result through the API. In your app, you can call the camera API or import a local image to obtain the bitmap, and then call the bitmap API of HUAWEI Scan Kit to decode the bitmap.
   MultiProcessor API:   The app passes frame data through the MultiProcessor API for decoding, and detects barcodes along with multiple objects such as faces, using the same technology as HUAWEI ML Kit.
   Generate Code API:    The app allow you to generate barcode.

## Getting Started

   1. Check whether the Android studio development environment is ready. Open the sample code project directory with file "build.gradle" in Android Studio. Run TestApp on your divice or simulator which have installed latest Huawei Mobile Service(HMS).
   2. Register a [HUAWEI account](https://developer.huawei.com/consumer/en/).
   3. Create an app and configure the app information in AppGallery Connect. 
   See details: [HUAWEI Game Service Development Preparation](https://developer.huawei.com/consumer/en/doc/development/HMS-Guides/game-preparation-v4)
   4. To build this demo, please first import the demo in the Android Studio (3.x+).
   5. Configure the sample code:
   (1) Download the file "agconnect-services.json" of the app on AGC, and add the file to the app root directory(\app) of the demo. 
   (2) Change the value of applicationid in the app-level build.gradle file of the sample project to the package name of your app.
   6. Run the sample on your Android device or emulator.

## Supported Environments
   Compile using Android Studio and JDK1.8

## Result
   HmsScan returns the scanning result
	
##  License
   GameSeviceKit sample is licensed under the: [Apache License, version 2.0](http://www.apache.org/licenses/LICENSE-2.0).
  