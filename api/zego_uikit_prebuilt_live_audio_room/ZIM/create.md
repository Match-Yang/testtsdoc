


# create method








[ZIM](../../zego_uikit_prebuilt_live_audio_room/ZIM-class.md)? create
([ZIMAppConfig](../../zego_uikit_prebuilt_live_audio_room/ZIMAppConfig-class.md) config)





<p>Create a ZIM instance.</p>
<p>You need to create and initialize an ZIM instance before calling any other function.
The SDK supports the creation of multiple ZIM instances.</p>
<p><code>config</code> appID and appSign issued by ZEGO for developers, Please apply at the ZEGO console.</p>



## Implementation

```dart
static ZIM? create(ZIMAppConfig config) {
  return ZIMManager.createEngine(config);
}
```







