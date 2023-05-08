


# locationAlways constant







[PermissionWithService](../../zego_uikit_prebuilt_live_audio_room/PermissionWithService-class.md) const locationAlways
  




<p>Android:
When running on Android &lt; Q: Fine and Coarse Location
When running on Android Q and above: Background Location Permission
iOS: CoreLocation - Always
When requesting this permission the user needs to grant permission
for the <code>locationWhenInUse</code> permission first, clicking on
  the <code>Àllow While Using App</code> option on the popup.
  After allowing the permission the user can request the <code>locationAlways</code>
  permission and can click on the <code>Change To Always Allow</code> option.</p>



## Implementation

```dart
static const locationAlways = PermissionWithService._(4);
```







