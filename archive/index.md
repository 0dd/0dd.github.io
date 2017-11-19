---
title: Design of an iOS App to create Live Wallpaper for previewing user's schedule by 3D Touch
date: 2017-09-16 21:34:02
---

## Background 

![3Dtouch](https://ws2.sinaimg.cn/large/006tNc79gy1flnq4tvifcj308i04lglg.jpg)


Image Source:https://appadvice.com/appnn/2015/08/what-will-force-touch-mean-for-the-iphone

**Force Touch** is a technology developed by [Apple Inc.](https://en.wikipedia.org/wiki/Apple_Inc.) that enables [trackpads](https://en.wikipedia.org/wiki/Touchpad) and [touchscreens](https://en.wikipedia.org/wiki/Touchscreen) to distinguish between different levels of force being applied to their surfaces.[^1] 

**3D Touch** is the new technology that launched by Apple for iPhone 6s and iPhone 6s Plus, which could be used to sense how deeply user press the display. [^2]

From the developer guide, this feature are mainly used for:

1. Quick Action
2. Peek and pop
3. Pressure Sensitivity

## Introduction 

In this case, we will mainly discuss about the usage of Peek and Pop. Peek and Pop is mainly used for the user to preview the content on screen. This  App's purpose is to create  a Live Photo[^3] used for the wallpaper.  The Wallpaper contained two images layers. One is the wallpaper layer, another is the layer of information create by the user. 

The users want to create a time schedule or other information images on their own then use this App to make it overlay on the original image. The user could preview the information layer by pressing the sensitive screen and peek the information there.

## Method 

This application is mainly used for combining the two layer in to one live photo image. 

First, the user are wanted to prepare two images on their own. 

To compose two of  the images, this application are wanted to get the access to the photo library. 





[^1]: Force Touch. (2017, September 15). In *Wikipedia*. Retrieved from https://en.wikipedia.org/w/index.php?title=Force_Touch&oldid=800780164
[^2]: 3D Touch - iOS - Apple Developer. (n.d.). Retrieved September 16, 2017, from https://developer.apple.com/ios/3d-touch/
[^3]: Take and edit Live Photos. (n.d.). Retrieved September 16, 2017, from https://support.apple.com/en-us/HT207310