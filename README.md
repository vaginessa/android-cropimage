# Android CropImage

<img src="https://cdn.rawgit.com/lvillani/android-cropimage/f55253d2be3e6c28a06dd8bdd1e45aa7fd0b22a1/logo.svg" align="right" width="200" height="200"/>

[![License](http://img.shields.io/badge/license-Apache%202.0-blue.svg?style=flat)](http://choosealicense.com/licenses/apache-2.0/)

--------------------------------------------------------------------------------

The `CropImage` activity extracted from `Gallery.apk` (AOSP 4.4.4). Compatible
with Android API Level 15 and up.


## Android Studio and Gradle

The project was created with Android Studio and uses the Gradle build system.


## Intent-based API

The `CropImage` activity is controlled by an Intent-based API. Please use the wrapper class
[CropImageIntentBuilder](CropImage/src/main/java/com/android/camera/CropImageIntentBuilder.java)
for a type-safe interface.


## Example Project

It is contained inside the `CropImageExample` module.


## Gradle/Maven Repository

There's a [Gradle/Maven repository](https://github.com/lvillani/android-cropimage/tree/gh-pages)
available at <http://lorenzo.villani.me/android-cropimage/>.

In your top-level `build.gradle` add the address of the Maven repository to the `repositories`
section so that it looks like:

```groovy
repositories {
    mavenCentral()

    maven {
        url 'http://lorenzo.villani.me/android-cropimage/'
    }
}
```

Then add the dependency to your `dependencies` section:

```groovy
compile 'me.villani.lorenzo.android:android-cropimage:1.0.1'
```


## Donating

Support this project and [others by Lorenzo Villani](https://github.com/lvillani/) via
[gittip](https://www.gittip.com/lvillani/).

[![Support via Gittip](https://cdn.rawgit.com/lvillani/gittip-badge/v1.0.0/dist/gittip.svg)](https://www.gittip.com/lvillani/)
