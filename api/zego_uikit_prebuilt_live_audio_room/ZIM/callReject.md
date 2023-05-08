


# callReject method








Future&lt;[ZIMCallRejectionSentResult](../../zego_uikit_prebuilt_live_audio_room/ZIMCallRejectionSentResult-class.md)> callReject
(String callID, [ZIMCallRejectConfig](../../zego_uikit_prebuilt_live_audio_room/ZIMCallRejectConfig-class.md) config)





<p>Supported versions: 2.1.5 and above.</p>
<p>Detail description: When the calling party initiates a call invitation, the called party can reject the call invitation through this interface.</p>
<p>Service scenario: When you need to reject the call invitation initiated earlier, you can use this interface to reject the call invitation.</p>
<p>When to call: It can be called after creating a ZIM instance through <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/create.md">create</a>.</p>
<p>Note: The callee will fail to reject the uninvited callid.</p>
<p><code>callID</code> The ID of the call invitation to be rejected.
<code>config</code> Related configuration for rejecting call invitations.</p>



## Implementation

```dart
Future<ZIMCallRejectionSentResult> callReject(
    String callID, ZIMCallRejectConfig config);
```







