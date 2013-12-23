Prerequisites: http://skl.me/#building-your-first-android-app

In order to compile this project, you need to set the `ANDROID_HOME` environment variable to the location the Android
SDK, e.g.:

```
export ANDROID_HOME=/usr/local/android-sdk
```

The Android Support Library also needs to be linked into the `libs` dir:

```
ln -s /usr/local/android-sdk/extras/android/support/v4/android-support-v4.jar libs/
```
