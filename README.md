# Mini App

## Problem

Device registration and configuration is cumbersome.

## Solution

Provide a multi-platform application featuring:

- Reduced connectivity barriers

- Plug pre-configurations

  - Schedule

  - Sentry

  - Strobe

### Set Up

  **Node 8.3 or better**

  `brew isntall node`

  **Watchmen**: watch changes to the file system

  `brew install watchmen`

  **Xcode Command Line Tools**

  `xcode-select --install`

  **iOS Simulator in Xcode**

  - Open Xcode > Preferences
  - Select the Components tab
  - Select a simulator

  **CocoaPods**: dependency manager for Swift and Objective-C Cocoa projects

  `sudo gem install cocoapods`

### Run

  **Run instructions for iOS**:
    - `cd ~/MiniApp && npx react-native run-ios`
    or
    - Open `MiniApp/ios/MiniApp.xcworkspace` in Xcode or run `xed -b ios`
    - Hit the Run button

  **Run instructions for Android**:
    - Have an Android emulator running (quickest way to get started), or a device connected.
    - `cd ~/MiniApp && npx react-native run-android`

