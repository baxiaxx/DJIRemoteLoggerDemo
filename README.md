# iOS-DJIRemoteLoggerDemo

## Introduction

This DJIRemoteLoggerDemo is designed for you to gain a better understanding of the DJI Remote Logger Tool. It will teach you how to use it for showing application log messages on a simple webpage.

## Requirements

 - iOS 9.0+
 - Xcode 8.0+
 - DJI iOS SDK 3.4.1

## SDK Installation with CocoaPods

Since this project has been integrated with [DJI iOS SDK CocoaPods](https://cocoapods.org/pods/DJI-SDK-iOS) now, please check the following steps to install **DJISDK.framework** using CocoaPods after you downloading this project:

**1.** Install CocoaPods

Open Terminal and change to the download project's directory, enter the following command to install it:

~~~
sudo gem install cocoapods
~~~

The process may take a long time, please wait. For further installation instructions, please check [this guides](https://guides.cocoapods.org/using/getting-started.html#getting-started).

**2.** Install SDK with CocoaPods in the Project

Run the following command in the project's directory:

~~~
pod install
~~~

If you install it successfully, you may get the messages similar to the followings:

~~~
Analyzing dependencies
Downloading dependencies
Installing DJI-SDK-iOS (3.4.1)
Generating Pods project
Integrating client project

[!] Please close any current Xcode sessions and use `DJIRemoteLoggerDemo.xcworkspace` for this project from now on.
Pod installation complete! There is 1 dependency from the Podfile and 1 total pod
installed.
~~~

## Tutorial

For this demo's tutorial: **DJI Remote Logger Tutorial**, please refer to <https://developer.dji.com/mobile-sdk/documentation/ios-tutorials/RemoteLoggerDemo.html>.

## Feedback

We’d love to hear your feedback for this demo and tutorial.

Please use **Github Issue** or **email** [oliver.ou@dji.com](oliver.ou@dji.com) when you meet any problems of using this demo. At a minimum please let us know:

* Which DJI Product you are using?
* Which iOS Device and iOS version you are using?
* A short description of your problem includes debug logs or screenshots.
* Any bugs or typos you come across.

## License

iOS-DJIRemoteLoggerDemo is available under the MIT license. Please see the LICENSE file for more info.
