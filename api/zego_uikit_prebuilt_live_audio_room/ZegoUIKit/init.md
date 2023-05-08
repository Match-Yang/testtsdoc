


# init method








Future&lt;void> init
({required int appID, String appSign = '', [ZegoScenario](../../zego_uikit_prebuilt_live_audio_room/ZegoScenario.md) scenario = ZegoScenario.Default})





<p>init</p>



## Implementation

```dart
Future<void> init(
    {required int appID,
    String appSign = '',
    ZegoScenario scenario = ZegoScenario.Default}) async {
  return ZegoUIKitCore.shared
      .init(appID: appID, appSign: appSign, scenario: scenario);
}
```







