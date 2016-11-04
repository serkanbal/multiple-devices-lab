---
title: Designing for Multiple Devices
type: Lab
duration: "1:25"
creator: Yuliya Kaleda (NYC)
---




# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png)  Designing for Multiple Devices

## Introduction  
The lab is focused on getting you to practice creating apps to support different SDKs, languages, layouts, and dimensions. You need to create an app that looks like the screenshots below. This will require you to create layouts for different orientations, support multiple languages, and effectively use various parts of the resources directory.

## Exercise  

#### Requirements  

Your app must support the following:

- minSdkVersion - Jelly Bean
- targetSdkVersion - Nougat
- English, French and Spanish languages
- portrait and landscape orientation, separate layouts for each
- absence of hardcoded strings, Your app should refer to the string.xml file
- icons to be generated through Android Vector Asset Studio of the size 40dpx40dp
- textSize of the TextView to be 20sp and stored in dimens.xml rather than a hardcoded value  

#### Bonus  
- create a separate layout file to support tablet size devices

## Deliverable

The app should eventually look like:
<p align="center">
  <a href="screenshots/portrait.png"><img src="screenshots/portrait.png" height="300"/></a>      <a href="screenshots/landscape.png"><img src="screenshots/landscape.png" height="200" width="380"/></a>
</p>

When the button is clicked the icon and text should change:
<p align="center">
  <a href="screenshots/portrait_clicked.png"><img src="screenshots/portrait_clicked.png" height="300"/></a>         <a href="screenshots/landscape_clicked.png"><img src="screenshots/landscape_clicked.png" height="200" width="380"/></a>
</p>

## Resources:
- [Take a look at the lesson notes](https://github.com/generalassembly-studio/ADI-curriculum/tree/designing-for-multiple-devices-lesson/resources/07-android-technologies-and-services/designing-for-multiple-devices)
