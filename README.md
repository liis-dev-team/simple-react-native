# simple-react-native
<br/>
<br/>
<p align="center">
Welcome to Simple React Native! Useful libraries, instructions, tutorials and more.
</p>
<br/>
<br/>

# FAQ
 - To add categories use [DocToc](https://github.com/thlorenz/doctoc)
 - When you add a new library, put near it hardmeter 💚 💛 ❤

# Categories
<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [Animation](#animation)
- [Integrations](#integrations)
- [Storage](#storage)
- [System](#system)
- [Utils](#utils)
- [UI](#ui)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Animation

### [react-native-animatable](https://github.com/oblador/react-native-animatable) 💚

Standard set of easy to use animations.

### [lottie-react-native](https://github.com/airbnb/lottie-react-native) ? 

A mobile library that parses Adobe After Effects animations exported as JSON with bodymovin and renders them natively on mobile.
## Integrations
### [react-native-google-signin](https://github.com/apptailor/react-native-google-signin) 💛

Google Signin for your react native applications

## Storage
### [react-native-mmkv](https://github.com/mrousavy/react-native-mmkv) 💛

The fastest key/value storage for React Native.

Problems: 
-  Can't use remote debugging (e.g. with Chrome). Instead, you should use Flipper.

## System

### [react-native-iap](https://react-native-iap.dooboolab.com/docs/intro)❤

React-native native module for In-App Purchase.

 Problems: 
- Test only in a real devices

## Utils

### [patch-package](https://github.com/ds300/patch-package)💚

Patch-package lets app authors instantly make and keep fixes to dependencies.

Very useful if you want to fix a third party library.

### [react-native-config](https://github.com/luggit/react-native-config)💚 

Config variables for React Native apps

### [babel-plugin-transform-remove-console](https://babeljs.io/docs/en/babel-plugin-transform-remove-console/) 💛

Delete all console.log from production

Problems: 
- [Problems to set babel.config.js correctly](https://stackoverflow.com/questions/57692298/react-native-0-60-3-babel-plugin-transform-remove-console-not-working)

## UI
### [react-native-blur](https://github.com/Kureev/react-native-blur) ❤

React Native Blur component

Problems: 
- [you need to patch app for correct work on android](https://github.com/Kureev/react-native-blur/pull/411#issuecomment-818396825)
- confilicts with React Native Reanimated 2

 ### [react-native-calendars](https://github.com/wix/react-native-calendars) 💛
 
 React Native Calendar Components

 Problems: 
- Very hard customization (if you build something serious, build your own calendar)

### [react-navigation/drawer](https://github.com/react-navigation/react-navigation/tree/main/packages/drawer) 💚

React Native Drawer component

 Problems: 
- Can't use navigation headers due to flickering issues. Need to use your custom ones,

### [react-native-orientation-locker](https://github.com/wonday/react-native-orientation-locker) 💚

The best library to use when you need to do something with device orientation.

 Problems: 
- Imperative orientation change doesn't work out of the box on iPad. You need to disable all orientations except portrait in Xcode for it to work. Yet this brings the problem when you launch your app your splash Screen will be displayed only in the portrait mode

### [react-native-popover-view](https://github.com/steffeydev/react-native-popover-view) 💚

React Native Popover component 


### [react-native-skeleton-placeholder](https://github.com/chramos/react-native-skeleton-placeholder) 💚

React Native Skeleton preloader component

 Problems: 
- Can't place skeleton inside another skeleton.

### [react-native-reanimated-carousel](https://github.com/dohooo/react-native-reanimated-carousel) 💛

Best React native carousel library. Great docs and examples. Pretty simple to start. You can do a lot of advanced stuff with this library.
For example: Apple carousel time picker



