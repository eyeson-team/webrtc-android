# WebRTC Android

Precompiled WebRTC library for Android

# Installation
Add [JitPack](https://jitpack.io/) to your root `build.gradle` at the end of repositories:
```gradle
allprojects {
	repositories {
		...
		maven { url 'https://jitpack.io' }
	}
}
```

Add the dependency to your app-level `build.gradle`. Latest version: [![](https://jitpack.io/v/eyeson-team/webrtc-android.svg)](https://jitpack.io/#eyeson-team/webrtc-android)

```gradle
dependencies {
	implementation 'com.github.eyeson-team:webrtc-android:VERSION'
}
```
# Desugaring 
Due to the use of OpenJDK 17 [desugaring](https://developer.android.com/studio/write/java11-nio-support-table) may be necessary.