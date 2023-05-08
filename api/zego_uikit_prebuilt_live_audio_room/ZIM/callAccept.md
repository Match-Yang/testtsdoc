


# callAccept method








Future&lt;[ZIMCallAcceptanceSentResult](../../zego_uikit_prebuilt_live_audio_room/ZIMCallAcceptanceSentResult-class.md)> callAccept
(String callID, [ZIMCallAcceptConfig](../../zego_uikit_prebuilt_live_audio_room/ZIMCallAcceptConfig-class.md) config)





<p>Supported versions: 2.1.5 and above.</p>
<p>Detail description: When the calling party initiates a call invitation, the called party can accept the call invitation through this interface.</p>
<p>Service scenario: When you need to accept the call invitation initiated earlier, you can accept the call invitation through this interface.</p>
<p>When to call: It can be called after creating a ZIM instance through <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/create.md">create</a>.</p>
<p>Note: The callee will fail to accept an uninvited callid.</p>
<p><code>callID</code> The call invitation ID to accept.
<code>config</code>  config.</p>



## Implementation

```dart
Future<ZIMCallAcceptanceSentResult> callAccept(
    String callID, ZIMCallAcceptConfig config);
```







