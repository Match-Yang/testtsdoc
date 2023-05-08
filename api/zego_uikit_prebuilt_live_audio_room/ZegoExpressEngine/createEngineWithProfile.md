


# createEngineWithProfile method








Future&lt;void> createEngineWithProfile
([ZegoEngineProfile](../../zego_uikit_prebuilt_live_audio_room/ZegoEngineProfile-class.md) profile)





<p>Create ZegoExpressEngine singleton object and initialize SDK.</p>
<p>Available since: 2.14.0
Description: Create ZegoExpressEngine singleton object and initialize SDK.
When to call: The engine needs to be created before calling other functions.
Restrictions: None.
Caution: The SDK only supports the creation of one instance of ZegoExpressEngine. Multiple calls to this function return the same object.</p>
<ul>
<li><code>profile</code> The basic configuration information is used to create the engine.</li>
</ul>



## Implementation

```dart
static Future<void> createEngineWithProfile(ZegoEngineProfile profile) async {
  return await ZegoExpressImpl.createEngineWithProfile(profile);
}
```







