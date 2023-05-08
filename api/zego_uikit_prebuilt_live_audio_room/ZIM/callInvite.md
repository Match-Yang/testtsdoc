


# callInvite method








Future&lt;[ZIMCallInvitationSentResult](../../zego_uikit_prebuilt_live_audio_room/ZIMCallInvitationSentResult-class.md)> callInvite
(List&lt;String> invitees, [ZIMCallInviteConfig](../../zego_uikit_prebuilt_live_audio_room/ZIMCallInviteConfig-class.md) config)





<p>Supported versions: 2.1.5 and above.</p>
<p>Detail description: When the caller initiates a call invitation, the called party can use <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/callAccept.md">callAccept</a> to accept the call invitation or <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/callReject.md">callReject</a> to reject the invitation.</p>
<p>Business scenario: When you need to initiate a call invitation, you can create a unique callid through this interface to maintain this call invitation.</p>
<p>When to call: It can be called after creating a ZIM instance through <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/create.md">create</a>.</p>
<p>Note: The call invitation has a timeout period, and the call invitation will end when the timeout period expires.</p>
<p><code>invitees</code> list of invitees.
<code>config</code> Call Invitation Related Configuration.</p>



## Implementation

```dart
Future<ZIMCallInvitationSentResult> callInvite(
    List<String> invitees, ZIMCallInviteConfig config);
```







