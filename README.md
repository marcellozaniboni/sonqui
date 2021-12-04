# About sonqui
This is small "one-tap app" for sharing quickly geolocation data with map links.
This software is provided under the terms of the GNU General Public License (GPL) version 2. You can find more details here [gnu.org/licenses](https://www.gnu.org/licenses/).
I used the following third party technologies for developing this app: they really simplified the job, so thank you very very much!

* OpenJDK, Android Studio and Gradle Build Tool
* Apache Cordova
* Apache Cordova plugins: cordova-plugin-dialogs, cordova-plugin-device, cordova-clipboard, cordova-plugin-x-socialsharing, cordova-plugin-geolocation, cordova-plugin-app-exit cordova-plugin-insomnia
* W3.CSS by W3Schools

## How to build
Follow the guides online and install Java, Android Studio and Apache Cordova. Then create the project directory
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

## Supported platforms
* Android
