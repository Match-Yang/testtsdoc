


# callCancel method








Future&lt;[ZIMCallCancelSentResult](../../zego_uikit_prebuilt_live_audio_room/ZIMCallCancelSentResult-class.md)> callCancel
(List&lt;String> invitees, String callID, [ZIMCallCancelConfig](../../zego_uikit_prebuilt_live_audio_room/ZIMCallCancelConfig-class.md) config)





<p>Supported versions: 2.1.5 and above.</p>
<p>Detail description: After the caller initiates a call invitation, the call invitation can be canceled through this interface before the timeout period.</p>
<p>Business scenario: When you need to cancel the call invitation initiated before, you can cancel the call invitation through this interface.</p>
<p>When to call: It can be called after creating a ZIM instance through <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/create.md">create</a>.</p>
<p>Note: Canceling the call invitation after the timeout period of the call invitation expires will fail.</p>
<p><code>invitees</code> List of invitees.
<code>callID</code> callID.
<code>config</code> Cancel the related configuration of call invitation.</p>



## Implementation

```dart
Future<ZIMCallCancelSentResult> callCancel(
    List<String> invitees, String callID, ZIMCallCancelConfig config);
```







