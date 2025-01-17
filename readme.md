# Rust with Android Studio or Xcode iOS


## Android Studio

* Android Studio Arctic Fox | 2020.3.1 Patch 2
* Android SDK Platform 31
* Android NDK 22.1.7171670
* Android SDK Build-Tools 31.0.0
* Android SDK Command-line Tools
* Android SDK Platform-Tools

![img](./sdk.png)



## Rust

Install rust on your PC from [rustup](https://rustup.rs), 
then add some Android targets (arm64, arm, x86_64, x86) for rust.
```
rustup target add aarch64-linux-android armv7-linux-androideabi i686-linux-android x86_64-linux-android
```


## Python

Install [Python](https://www.python.org/downloads/) on your PC.


## iOS

- macOS / Xcode
- `curl https://sh.rustup.rs -sSf | sh`
- `rustup target add aarch64-apple-ios x86_64-apple-ios`
- `cargo install cargo-lipo`
- `cargo lipo --release`


## References
- [Rust Android Gradle Plugin](https://github.com/mozilla/rust-android-gradle)
- [Workshop: Use Rust in iOS Apps](https://github.com/thombles/dw2019rust)
- [One more plugin to build Rust for Android](https://dev.to/willir/one-more-plugin-to-build-rust-for-android-125h)
- [Cargo NDK for Android projects](https://github.com/willir/cargo-ndk-android-gradle)
- [Running Rust on Android](https://blog.svgames.pl/article/running-rust-on-android)
- [Building and Deploying a Rust library on iOS](https://mozilla.github.io/firefox-browser-architecture/experiments/2017-09-06-rust-on-ios.html)
- [Building and Deploying a Rust library on Android](https://mozilla.github.io/firefox-browser-architecture/experiments/2017-09-21-rust-on-android.html)


Done!
