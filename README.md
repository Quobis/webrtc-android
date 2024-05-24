# webrtc-android

This repository contains precompiled versions of [WebRTC](https://webrtc.org/) for android, an open-source project that enables real-time communication in browsers and mobile applications via simple APIs.

## Latest version

The precompiled WebRTC for Android versions found in this repository are based on the official stable releases of WebRTC. We strive to publish new versions as soon as possible after the official releases are published.

You can find a list of available versions and their release dates at the following link:

[Webrtc releases](https://chromiumdash.appspot.com/releases?platform=Android)

GoogleWebrtc is available on Github Packages

```
maven {
    name = "GitHubPackages"
    url = uri("https://maven.pkg.github.com/quobis/webrtc-android")
}
```

```
implementation "org.webrtc:google-webrtc:125.0.0"
```


**Note:**

-   Precompiled WebRTC for Android versions are not compatible with all versions of Android. Please refer to the WebRTC documentation for more information on compatibility requirements.
-   It is important to use the latest available version of the precompiled WebRTC for Android library. Newer versions may include bug fixes and performance improvements.

