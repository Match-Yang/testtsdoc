


# isPermanentlyDenied property









bool isPermanentlyDenied
  




<p><em>On Android:</em>
If the user denied access to the requested feature and selected to never
again show a request for this permission (pre API 30) or the user denied
permissions for a second time (API 30 and higher).
The user may still change the permission status in the settings.</p>
<p><em>On iOS:</em>
If the user has denied acces to the requested feature.
The user may still change the permission status in the settings</p>
<p>WARNING: This can only be determined AFTER requesting this permission.
Therefore make a <code>request</code> call first.</p>



## Implementation

```dart
bool get isPermanentlyDenied => this == PermissionStatus.permanentlyDenied;
```








