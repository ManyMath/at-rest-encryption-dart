# `are`

## Setup

### Native assets

Native assets is currently an experimental feature that is available in Flutter's `master` branch behind an optional Flutter config:

```
flutter config --enable-native-assets
```

See [this tracking issue](https://github.com/flutter/flutter/issues/129757) and [this milestone](https://github.com/dart-lang/native/milestone/15) for the eventual inclusion of native assets in a release.

### Quick setup

```
git clone git@github.com:ManyMath/at-rest-encryption-dart
cd at-rest-encryption-dart
dart pub get
dart --enable-experiment=native-assets run example/are_example.dart
```
