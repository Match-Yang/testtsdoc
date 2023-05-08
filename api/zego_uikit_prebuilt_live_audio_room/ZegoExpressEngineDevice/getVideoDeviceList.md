


# getVideoDeviceList method








Future&lt;List&lt;[ZegoDeviceInfo](../../zego_uikit_prebuilt_live_audio_room/ZegoDeviceInfo-class.md)>> getVideoDeviceList
()





<p>Gets a list of video devices.</p>
<p>Only for Windows / macOS / Web
Note: This function is only available in ZegoExpressVideo SDK!</p>
<ul>
<li>Returns Video device List</li>
</ul>



## Implementation

```dart
Future<List<ZegoDeviceInfo>> getVideoDeviceList() async {
  return await ZegoExpressImpl.instance.getVideoDeviceList();
}
```







