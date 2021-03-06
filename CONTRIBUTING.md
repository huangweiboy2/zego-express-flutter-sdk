# Contribute your code

We are glad you are here! Everyone is welcome to contribute code via pull requests, to help people asking for help, to add to our documentation, or to help out in any other way.

This document briefly describes some guidance on how you can contribute to this repository.

## Source code structures

### Dart

1. ***[lib/src/zego_express_api.dart](lib/src/zego_express_api.dart)*** & *other dart file with **zego_express_api** prefix*: Dart bridge interface for implementation.

2. ***[lib/src/zego_express_impl.dart](lib/src/zego_express_impl.dart)***: Dart implementation of calls the native method with method channel.

3. ***[lib/src/zego_express_platform_view_utils.dart](lib/src/zego_express_platform_view_utils.dart)***: Dart utility methods for managing platform view.

4. ***[lib/src/zego_express_texture_render_utils.dart](lib/src/zego_express_texture_render_utils.dart)***: Dart utility methods for managing texture renderer.

- ***[example](example)***: Example demo for quick start.

### iOS

1. ***[ios/Classes/ZegoExpressEnginePlugin.m](ios/Classes/ZegoExpressEnginePlugin.m)***: iOS native implementation, handle the life cycle of flutter plugin.

2. ***[ios/Classes/ZegoExpressEngineMethodHandler.m](ios/Classes/ZegoExpressEngineMethodHandler.m)***: iOS native implementation, handle the method call of dart.

3. ***[ios/Classes/ZegoExpressEngineEventHandler.m](ios/Classes/ZegoExpressEngineEventHandler.m)***: iOS native implementation, handle native callbacks.

4. ***[ios/Classes/ZegoPlatformView.m](ios/Classes/ZegoPlatformView.m)*** & ***[ios/Classes/ZegoPlatformViewFactory.m](ios/Classes/ZegoPlatformViewFactory.m)***: iOS native implementation, handle platform view.

5. ***[ios/Classes/ZegoTextureRenderer.m](ios/Classes/ZegoTextureRenderer.m)*** & ***[ios/Classes/ZegoTextureRendererController.m](ios/Classes/ZegoTextureRendererController.m)***: iOS native implementation, handle texture renderer.

### Android

1. ***[android/src/main/java/im/zego/zego_express_engine/ZegoExpressEnginePlugin.java](android/src/main/java/im/zego/zego_express_engine/ZegoExpressEnginePlugin.java)***: Android native implementation, handle the life cycle of flutter plugin.

2. ***[android/src/main/java/im/zego/zego_express_engine/ZegoExpressEngineMethodHandler.java](android/src/main/java/im/zego/zego_express_engine/ZegoExpressEngineMethodHandler.java)***: Android native implementation, handle the method call of dart.

3. ***[android/src/main/java/im/zego/zego_express_engine/ZegoExpressEngineEventHandler.java](android/src/main/java/im/zego/zego_express_engine/ZegoExpressEngineEventHandler.java)***: Android native implementation, handle native callbacks.

4. ***[android/src/main/java/im/zego/zego_express_engine/ZegoPlatformView.java](android/src/main/java/im/zego/zego_express_engine/ZegoPlatformView.java)*** & ***[android/src/main/java/im/zego/zego_express_engine/ZegoPlatformViewFactory.java](android/src/main/java/im/zego/zego_express_engine/ZegoPlatformViewFactory.java)***: Android native implementation, handle platform view.

5. ***[android/src/main/java/im/zego/zego_express_engine/ZegoTextureRenderer.java](android/src/main/java/im/zego/zego_express_engine/ZegoTextureRenderer.java)*** & ***[android/src/main/java/im/zego/zego_express_engine/ZegoTextureRendererController.java](android/src/main/java/im/zego/zego_express_engine/ZegoTextureRendererController.java)***: Android native implementation, handle texture renderer.

> The following materials may be helpful to create Pull Request:

- [Effective Dart](https://www.dartlang.org/guides/language/effective-dart)
- [Style guide for flutter](https://github.com/flutter/flutter/wiki/Style-guide-for-Flutter-repo)
