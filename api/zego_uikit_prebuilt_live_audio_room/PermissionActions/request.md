


# request method








Future&lt;[PermissionStatus](../../zego_uikit_prebuilt_live_audio_room/PermissionStatus.md)> request
()





<p>Request the user for access to this <a href="../../zego_uikit_prebuilt_live_audio_room/Permission-class.md">Permission</a>, if access hasn't already
been grant access before.</p>
<p>Returns the new <code>PermissionStatus</code>.</p>



## Implementation

```dart
Future<PermissionStatus> request() async {
  final permissionStatus = (await [this].request())[this];
  return permissionStatus ?? PermissionStatus.denied;
}
```







