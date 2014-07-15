# fdk-aac build script for iOS

Shell script to build fdk-aac for use in iOS apps.

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

## Caveat

No arm64 support yet
