#Cordova Practice

##Command

Create App and build
```
npm install -g cordova
cordova create hello com.example.hello Helloworld
cd hello
cordova platform add android --save
cordova platform ls
cordova build android
```
log...
```
Total time: 2 mins 37.15 secs
Built the following apk(s):
  C:/cordova-practice/hello/platforms/android/build/outputs/apk/android-debug.apk
```

##References
- [Cordova Apache](https://cordova.apache.org/docs/en/latest/guide/cli/)

##Requirements
- IOS SDK
- [ANDROID SDK](https://developer.android.com/studio/index.html#downloads)
- Node
- Cordova

##Trouble Shooting
- [Sdk gralde/wrapper is empty](http://stackoverflow.com/questions/42613882/error-could-not-find-gradle-wrapper-within-android-sdk-might-need-to-update-yo)
