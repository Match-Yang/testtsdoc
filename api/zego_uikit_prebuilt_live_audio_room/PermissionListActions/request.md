


# request method








Future&lt;Map&lt;[Permission](../../zego_uikit_prebuilt_live_audio_room/Permission-class.md), [PermissionStatus](../../zego_uikit_prebuilt_live_audio_room/PermissionStatus.md)>> request
()





<p>Requests the user for access to these permissions, if they haven't already
been granted before.</p>
<p>Returns a <code>Map</code> containing the status per requested <a href="../../zego_uikit_prebuilt_live_audio_room/Permission-class.md">Permission</a>.</p>



## Implementation

```dart
Future<Map<Permission, PermissionStatus>> request() =>
    _handler.requestPermissions(this);
```







