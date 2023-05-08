


# updateUserExtendedData method








Future&lt;[ZIMUserExtendedDataUpdatedResult](../../zego_uikit_prebuilt_live_audio_room/ZIMUserExtendedDataUpdatedResult-class.md)> updateUserExtendedData
(String extendedData)





<p>Available since: 2.2.0 and above.</p>
<p>Description: Through this interface, you can update your user extended data.</p>
<p>When to call /Trigger: It is available only after calling <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/create.md">create</a> to create the instance and then calling <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/login.md">login</a> to login.</p>
<p><code>extendedData</code> the user extended data you want to update.</p>



## Implementation

```dart
Future<ZIMUserExtendedDataUpdatedResult> updateUserExtendedData(
    String extendedData);
```







