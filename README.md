Swift Language Weather
============
[![BuddyBuild](https://dashboard.buddybuild.com/api/statusImage?appID=562a9aac2492560100211378&branch=master&build=latest)](https://dashboard.buddybuild.com/apps/562a9aac2492560100211378/build/latest)
![Language](https://img.shields.io/badge/language-Swift%204-orange.svg)

**SwiftWeather** has renamed to **Swift Language Weather**. Because this repo is ranked number one in Google when we search "Swift Weather", I got an email from Swift Weather Company's lawyer to ask me to change the name because they said they are the owner of U.S. Trademark SWIFT WEATHER. After discussed with them, they were not happy with the name Swift**y**Weather. Now the new project name is **Swift Language Weather**.

**Swift Language Weather** is an iOS weather app developed in Swift 4. The app has been actively upgrading to adopt the latest features of iOS and Swift language.

## Notices
The current version is working with Xcode Version Xcode 9.1 (9B55). If you are using different Xcode version, please check out the previous releases. 

## Version 4
This version has been upgraded to support iOS 10+ only using Swift 4.

There is three major version of the app released before.

* V1.0 - Support iOS 7+ using CocoaPods and AFNetworking. 
* V2.0 - Support iOS 8+ using Carthage, Alamofire, and SwiftyJSON. 
* V2.1 -  Support iOS 8+ using Alamofire and SwiftyJSON. This version has removed Carthage because some developers don't have a paid Apple iOS developer account, and they have issues to build Carthage packages.
* V3.0 -  Support iOS 9+ and Swift 3.


## Screenshots


## Features
* Swift Programming Language
* Design-driven development - [Sketch design file ](https://raw.githubusercontent.com/0x0firebox/SwiftWeather/master/Design/SwiftWeather.sketch)

![Sketch design](https://raw.githubusercontent.com/0x0firebox/SwiftWeather/master/screenshots/SketchDesign.png)
 
* Custom UIView

![Custom UIView](https://raw.githubusercontent.com/0x0firebox/SwiftWeather/master/screenshots/Custom-UIView.png)

* `@IBDesignable` and `@IBInspectable` - Reusable UI components

![IBDesignable and IBInspectable](https://raw.githubusercontent.com/0x0firebox/SwiftWeather/master/screenshots/IBDesignable-IBInspectable.png)

* `UIStackView` 

![UIStackView](https://raw.githubusercontent.com/0x0firebox/SwiftWeather/master/screenshots/UIStackView.png)
 
* Size Classes - Support different devices with adaptive layout

![Size Classes](https://raw.githubusercontent.com/0x0firebox/SwiftWeather/master/screenshots/UIStackView-with-Size-Classes.png)

* MVVM - Reactively update `ViewController` UI from `ViewModel`
* Protocol-Oriented Programming - We use Protocol-Oriented Programming in [IBAnimatable open source project](https://github.com/IBAnimatable/IBAnimatable).
* Value-based programming - Use immutable value anywhere.
* Icon fonts － Use [Weather Icons](https://erikflowers.github.io/weather-icons/)
* [SwiftyJSON](https://github.com/SwiftyJSON/SwiftyJSON)
* Core Location
* App indexing like CoreSpotlight and `NSUserActivity`
* Unit Tests
* UI Tests
* Animations

## How to build

1) Clone the repository

```bash
$ git clone https://github.com/0x0firebox/SwiftLanguageWeather.git
```

2) Install pods

```bash
$ cd SwiftLanguageWeather
$ pod install
```

3) Open the workspace in Xcode

```bash
$ open "SwiftWeather.xcworkspace"
```

4) Sign up on [openweathermap.org/appid](http://openweathermap.org/appid) to get an appid

```bash
$ mkdir .access_tokens
$ echo "your-openweathermap-appid" > .access_tokens/openweathermap
```
*Please replace "your-openweathermap-appid" with your actual appid key.*
 
5) Compile and run the app in your simulator

6) If you don't see any data, please check "Simulator" -> "Debug" -> "Location" to change the location.

# Requirements

* Xcode 9
* iOS 10+
* Swift 4


