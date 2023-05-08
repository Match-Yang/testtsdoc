


# resetBeautyEffect method








Future&lt;void> resetBeautyEffect
()





<p>reset beauty effect</p>



## Implementation

```dart
Future<void> resetBeautyEffect() async {
  ZegoUIKitCore.shared.coreData.beautyParam =
      ZegoEffectsBeautyParam.defaultParam();
  await ZegoExpressEngine.instance
      .setEffectsBeautyParam(ZegoEffectsBeautyParam.defaultParam());
}
```







