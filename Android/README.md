# Awesome Titanium Hyperloop: Android
[![Appcelerator Titanium](http://www-static.appcelerator.com/badges/titanium-git-badge-sq.png)](http://appcelerator.com/titanium/)

## Why this README.md?
 I'd like to gather as much good information on Hyperloop and Android as possible.  
 There are several ways that you can use Hyperloop for Android developement
 - Reference Google Frameworks already on device
 - Use AARs and JARs

[Android Hyperloop Programming Guide](https://wiki.appcelerator.org/display/guides2/Android+Hyperloop+Programming+Guide) 
has information on running a demo application specifically for Android and you can learn how to use Hyperloop in your own project.

## List of Android Modules
- [Ti.AndroidCharts](https://github.com/loop-modules/Ti.AndroidCharts.) - This HyperLoop module allows you to use highly customizable Charts with the MPAndroidChart library: https://github.com/PhilJay/MPAndroidChart. This module was originally posted on LoopModules: https://loopmodules.com/downloads/ti-androidcharts/
- [Ti.Reprint](https://github.com/loop-modules/Ti.Reprint) - This HyperLoop module allows you to implement fingerprint recognition in your Android app.
- [Ti.FAB](https://github.com/loop-modules/Ti.FAB) - Ti.FAB is an Android Hyperloop wrapper of the native Floating Action Button component. A Floating Action Button represents the primary action in an application.
- [Ti.AndroidViewAnimations](https://github.com/loop-modules/Ti.AndroidViewAnimations) - Ti.AndroidViewAnimations is an Android Hyperloop wrapper of the AndroidViewAnimations library. It provides a wide range of different animations that can be applied to your Titanium components.
- [Ti.CalendarView](https://github.com/m1ga/Ti.CalendarView) - Axway Hyperloop Calendar View for Android

## Working with Google's Frameworks
Many of the basic Hyperloop examples are just this - extending built in frameworks.  You don't have to load any outside libraries to access this.

## Working with 3rd Party Frameworks (JARs and AARs)
You can include 3rd Party libraries into your project.  
Just put your .jar and .aar files in /app/platform/android/ and require them in your controllers. 

## Can I get some Gradle in here?
Long story short, I have heard no talk of Gradle integration.  This would be a top 3 wish of mine for Hyperloop!  
Do you have any idea of how to make it work?  Let's toss around some ideas! 

### More Examples
- **Submit a PR with some more examples!  Do it!**