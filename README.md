# fdk-aac build script for iOS

See https://github.com/kewlbear/FFmpeg-iOS for .xcframework support, integration with FFmpeg and more.

Shell script to build fdk-aac for use in iOS apps.

## Preparation

```
brew install automake libtool
fdk-aac-X.X.X/autogen.sh
```

## Usage

* Build all:

```
build-fdk-aac.sh
```

* Build for some architectures:

```
build-fdk-aac.sh armv7s x86_64
```

* Build universal library from separately built architectures:

```
build-fdk-aac.sh lipo
```
