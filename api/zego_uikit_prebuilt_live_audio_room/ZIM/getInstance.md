


# getInstance method








[ZIM](../../zego_uikit_prebuilt_live_audio_room/ZIM-class.md)? getInstance
()





<p>Get the SDK's instance</p>
<p>When you need to call <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/getInstance.md">getInstance</a> to get ZIM instance, Please call <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/create.md">create</a> first. Otherwise, this API will return null.</p>



## Implementation

```dart
static ZIM? getInstance() {
  return ZIMManager.getInstance();
}
```







