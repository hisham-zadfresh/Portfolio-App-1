Resume App
-----------------------

[![Build Status](https://travis-ci.org/kioko/pod-adddict.svg?branch=master)](https://travis-ci.org/kioko/pod-adddict)

PodAdddict is an open-source Android Podcast manager that fetches Podcast info from [iTunes Affiliate Resources API](https://affiliate.itunes.apple.com/resources/documentation/itunes-store-web-service-search-api/)

This project was developed as the final Capstone Project for [Udacity Android Developer Nanodegree Program.](https://www.udacity.com/course/android-developer-nanodegree-by-google--nd801)

##Screenshots

<p align="center">
  <img src="https://github.com/kioko/pod-adddict/blob/master/art/Pod-Addict-Collection.png" alt="Pod-Adddict"/>
</p>

<table>
  <tr >
    <td><img src="https://github.com/kioko/pod-adddict/blob/develop/art/Discover-Poscast.png" width="300"/></td>
    <td align="right"><img src="https://github.com/kioko/pod-adddict/blob/develop/art/Podcast-Detail.png" width="300"/></td>
  </tr>
   <tr >
      <td><img src="https://github.com/kioko/pod-adddict/blob/develop/art/Subscribed-Feeds.png" width="300"/></td>
      <td align="right"><img src="https://github.com/kioko/pod-adddict/blob/develop/art/PodCast-Episodes.png" width="300"/></td>
    </tr>
    <tr >
     <td><img src="https://github.com/kioko/pod-adddict/blob/master/art/Podcast-Full-Player.png" width="300"/></td>
     <td><img src="https://github.com/kioko/pod-adddict/blob/develop/art/Podcast-Player.png" width="300"/></td>
     </tr>
      <tr >
       <td><img src="https://github.com/kioko/pod-adddict/blob/develop/art/Expanded-Notificaiton.png" width="300"/></td>
        <td align="right"><img src="https://github.com/kioko/pod-adddict/blob/develop/art/Collapsed-Notification.png" width="300"/></td>
         </tr>
  <tr>
    <td colspan="2"><img src="https://github.com/kioko/pod-adddict/blob/develop/art/widget.png" width="300"/></td>
  </tr>
</table>

## Download APK
You can download the apk from: 

1. [Google Playstore](https://play.google.com/store/apps/details?id=com.thomaskioko.podadddict.app)
2. [Github Release](https://github.com/kioko/pod-adddict/releases/download/v1.0.0/Pod-Adddict-v1.0.apk)


## Requirements
* JDK Version 1.7 & above
* [Android SDK.](http://developer.android.com/sdk/index.html)
* Android SDK Tools
* Android SDK Build tools 23.0.2
* Android Support Repository
* Android Support library

## Google Play Services Setup.
This project uses Firebase and Google Analytics. You will need to generate the configuration file (`google-services.json`) and copy it to your `/app` dir. See links below

1. [Setup Firebase setup](https://firebase.google.com/docs/android/setup)
2. [Setup Google Analytics](https://developers.google.com/analytics/devguides/collection/android/v4/)


## Project Setup

This project is built with Gradle, the [Android Gradle plugin](http://tools.android.com/tech-docs/new-build-system/user-guide) Clone this repository inside your working folder. Import the `settings.gradle` file in the root folder into e.g. Android Studio. (You can also have a look at the `build.gradle` files on how the projects depend on another.)

* Start Android Studio
* Select "Open Project" and select the generated root Project folder
* You may be prompted with "Unlinked gradle project" -> Select "Import gradle project" and select
the option to use the gradle wrapper
* You may also be prompted to change to the appropriate SDK folder for your local machine
* Once the project has compiled -> run the project!


Contributing
============

#### Would you like to contribute code?

1. [Fork PodAdddict](https://github.com/kioko/pod-adddict).
2. Create a new branch ([using GitHub](https://help.github.com/articles/creating-and-deleting-branches-within-your-repository/)) or the command `git checkout -b branch-name dev`).
3. [Start a pull request](https://github.com/kioko/pod-adddict/compare). Reference [existing issues](https://github.com/kioko/pod-adddict/issues) when possible.

#### No code!
* You can [discuss a bug](https://github.com/kioko/pod-adddict/issues) or if it was not reported yet [submit a bug](https://github.com/kioko/pod-adddict/issues/new).


Libraries Used
============

1. [Retrofit](http://square.github.io/retrofit/)
2. [ButterKnife](http://jakewharton.github.io/butterknife/)
3. [Glide](https://github.com/bumptech/glide)
4. [Stetho](https://github.com/facebook/stetho)
5. [TriangleLabelView](https://github.com/shts/TriangleLabelView)
6. [CircleImageView](https://github.com/hdodenhof/CircleImageView)
7. [Recycler Gesture](https://github.com/netcosports/RecyclerGesture)
8. [AVLoadingIndicatorView](https://github.com/81813780/AVLoadingIndicatorView)
9. [Sublime Navigationview Library](https://github.com/vikramkakkar/SublimeNavigationView)

License
-------

    Copyright 2016 Tumur.B Alex

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.


