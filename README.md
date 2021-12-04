# About sonqui
sonqui is a small "one-tap app" for Android sharing quickly geolocation data with map links.
It gets the detailed technical geolocation data and generates map links for Google Maps, OpenStreetMap, Bing Maps, and Yandex Maps. It can also be used as a real-time speedometer.

This software displays no ads and is provided under the terms of the GNU General Public License (GPL) version 2. You can find more details here [gnu.org/licenses](https://www.gnu.org/licenses/) and here [gnu.org/licenses/old-licenses/gpl-2.0](https://www.gnu.org/licenses/old-licenses/gpl-2.0.html).
I used the following third party technologies for developing this app: they really simplified the job, so thank you very very much!

* OpenJDK, Android Studio and Gradle Build Tool
* Apache Cordova
* Apache Cordova plugins: cordova-plugin-dialogs, cordova-plugin-device, cordova-clipboard, cordova-plugin-x-socialsharing, cordova-plugin-geolocation, cordova-plugin-app-exit cordova-plugin-insomnia
* W3.CSS by W3Schools

## How to build
Follow the guides online and install Java, Android Studio (with SDK Platforms for Android 8.0 / API Level 26 and Android 9.0 / API Level 28), Gradle, Node.js, npm and Apache Cordova. Then create the project directory:

```
cordova create sonqui net.marcellozaniboni.sonqui "sonqui"
cd sonqui
cordova platform add browser
cordova platform add android@8.0.0
cordova plugin add cordova-plugin-dialogs
cordova plugin add cordova-plugin-device
cordova plugin add cordova-clipboard
cordova plugin add cordova-plugin-x-socialsharing
cordova plugin add cordova-plugin-geolocation
```

Now you can get the files from GitHub and copy/replace them in the project directory.

For UI testing purposes you can quickly run the app in a web browser using

```
cordova clean
cordova build browser
cordova run browser
```

...however in the web browser the app will run with limited functionalities.

You can build the Android app like this:

```
cordova clean
cordova build
cordova build --release
```

You'll find the output APKs in `platforms/android/app/build/outputs/apk/`

## Supported platforms
* Android

## Compiled binaries
* [sonqui-0.9.10-selfsigned.apk](https://github.com/marcellozaniboni/sonqui/releases/download/0.9.10/sonqui-0.9.10-selfsigned.apk)
* [sonqui-0.9.10-debug.apk](https://github.com/marcellozaniboni/sonqui/releases/download/0.9.10/sonqui-0.9.10-debug.apk)
