


# renewToken method








Future&lt;void> renewToken
(String roomID, String token)





<p>Renew token.</p>
<p>Available since: 2.8.0
Description: After the developer receives <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRoomTokenWillExpire.md">onRoomTokenWillExpire</a>, they can use this API to update the token to ensure that the subsequent RTC functions are normal.
Use cases: Used when the token is about to expire.
When to call /Trigger: After the developer receives <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/onRoomTokenWillExpire.md">onRoomTokenWillExpire</a>.
Restrictions: None.
Caution: The token contains important information such as the user's room permissions, publish stream permissions, and effective time, please refer to <a href="https://docs.zegocloud.com/article/11649">https://docs.zegocloud.com/article/11649</a>.
Related callbacks: None.
Related APIs: None.</p>
<ul>
<li><code>roomID</code> Room ID.</li>
<li><code>token</code> The token that needs to be renew.</li>
</ul>



## Implementation

```dart
Future<void> renewToken(String roomID, String token) async {
  return await ZegoExpressImpl.instance.renewToken(roomID, token);
}
```







