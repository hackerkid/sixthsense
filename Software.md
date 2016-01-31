# How to run the Software Component of SixthSense #

The prototype system runs on windows platform and majority of the code is written in C++ and C#. We will be uploading newer versions as it is being developed; this will also include a mobile version.

NOTE: We are moving the new code to Git this week. Meanwhile you can download it at the link below.

## WUW v0.1 beta ##
### Download ###
[v0.1](http://code.google.com/p/sixthsense/downloads/detail?name=wuw_v0.1.zip&can=2&q=)

or you can download latest release tag from: [github](https://github.com/sixthsense/sixthsense/tarball/0.1beta)

### Instructions for running WUW\_v0.1 ###

WUW\_v0.1 is the beta version of SixthSense code (WUW stands for Wear Ur World, a former name of the project). This version runs on Windows. Make sure you have Visual Studio and Direct X installed. Extract and copy the files from wuw\_v0.1.zip to any location on your computer. Open WUW01.sln (which is present in the folder "CODE") then click on F5 to debug it. If you debug it successfully, a black screen appears with a little square box on the right just hover your mouse around it and you will find Option tabs such as Camera, Tokens and Apps.

**Camera**: you can choose which camera to use and configure the camera settings here. You may need to mirror the camera here using the camera settings. It is also recommended to use fixed/manual white balance and exposure such that the camera image is stable and light independent.

**Tokens**: This version of code uses colored fingertips as markers. One need 4 different colors in order to run most of the Apps. We recommend to use Red, Yellow, Blue and Green (or colors that are different enough). We have also noticed that the matt colored tape/objects works better as they have less reflective changes. When you click on ‘Add Markers’, the screen starts blinking and after 4-5 secs it stops with a still picture so that you can add those markers on your hand as new markers. You can simply drag-select the colored marker on the screen by mouse cursor. Once you have all four markers (O, P, M, and N) added the software will start tracking the four markers. You can set the thresholds to better the tracking. You can save those markers and can reuse in subsequent executions, or can add new markers every time.

**Apps**: there are three ways to launch any application. Apps tab can let you choose the apps you want to load and run. One can also load apps from ‘Menu’. ‘Menu’ is triggered using Namaste gesture. Once on Menu screen you can choose the App by hand-click (Hand Click gesture works by moving the O marker and hiding P marker.

(Some of the Apps require some particular settings. There are also several types of gestures that are supported as of now. Details on Applications and Gestures will be added soon here.)

## [Contribute](http://code.google.com/p/sixthsense/wiki/Contribute) ##