# Change Log

## 1.14.0

1. Update native SDK to version 1.14.0

2. Add `loginMultiRoom`, `switchRoom`, `setRoomExtraInfo` APIs and `onRoomExtraInfoUpdate` callback

3. Optimize the callback log on the flutter native side

## 1.1.0

1. Update native SDK to version 1.12.3

2. Add `setANSMode`, `setAudioEqualizerGain`, `setVoiceChangerParam`, `setReverbParam`, `enableVirtualStereo` APIs

3. Add `Record` module with `startRecordingCapturedData`, `stopRecordingCapturedData`, `onCapturedDataRecordStateUpdate`, `onCapturedDataRecordProgressUpdate`

4. Add `getVideoConfig` implementation for Android

5. Fix issue of `stopMixerTask` for Android

## 0.15.1

- Fix the problem that the `codecID` parameter of `setVideoConfig` API does not take effect

## 0.15.0

- Update native SDK to version 1.11.4

## 0.14.2

- Fix the conversion issue of generic Map for some callbacks

## 0.14.1

1. Fix `enablePublishDirectToCDN` API

2. Fix `updateTextureRendererSize` API on Android

## 0.14.0

1. Update native SDK to version 1.10.0

2. Fix `updateTextureRendererSize` API on Android

3. Fix `onRoomOnlineUserCountUpdate` callback

## 0.13.1

- Fix mixer module issue

## 0.13.0

- Update native SDK to version 1.9.2

## 0.12.2

- Update native SDK to version 1.8.2

## 0.12.1

- Fix `onIMRecvCustomCommand` callback on iOS

## 0.12.0

1. Update native iOS SDK to version 1.8.0

2. Update native Android SDK to version 1.8.1

3. Fix some bugs in the IM module

## 0.11.1

- Update native SDK to version 1.7.9

## 0.11.0

1. Update native SDK to version 1.7.8

2. Optimize native method handler and callback handler

## 0.10.0

1. Add media player (audio only) module

2. Update native SDK to version 1.7.0

3. Add error code definition class

4. Fix iOS callback bug

## 0.9.3

- Fix type conversion issue in dart callback

## 0.9.2

- Update native SDK version to 1.6.0

## 0.9.1

1. Implement Android mixer API

2. Fix iOS mixer bug

## 0.9.0

- Initial release, with native SDK dependency version 1.5.5
