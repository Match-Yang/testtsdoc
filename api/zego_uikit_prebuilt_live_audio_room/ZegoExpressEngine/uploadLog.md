


# uploadLog method








Future&lt;void> uploadLog
()





<p>Uploads logs to the ZEGO server.</p>
<p>Available since: 1.1.0
Description: By default, SDK creates and prints log files in the App's default directory. Each log file defaults to a maximum of 5MB. Three log files are written over and over in a circular fashion. When calling this function, SDK will auto package and upload the log files to the ZEGO server.
Use cases: Developers can provide a business “feedback” channel in the App. When users feedback problems, they can call this function to upload the local log information of SDK to help locate user problems.
When to call: After <code>loginRoom</code> or <code>loginScene</code>.
Restrictions: If you call this interface repeatedly within 10 minutes, only the last call will take effect.
Caution: After calling this interface to upload logs, if you call <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/destroyEngine.md">destroyEngine</a> or exit the App too quickly, there may be a failure.It is recommended to wait a few seconds, and then call <a href="../../zego_uikit_prebuilt_live_audio_room/ZegoExpressEngine/destroyEngine.md">destroyEngine</a> or exit the App after receiving the upload success callback.</p>



## Implementation

```dart
Future<void> uploadLog() async {
  return await ZegoExpressImpl.instance.uploadLog();
}
```







