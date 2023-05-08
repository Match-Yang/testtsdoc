


# isPermanentlyDenied property









Future&lt;bool> isPermanentlyDenied
  




<p><em>On Android:</em>
If the user denied access to the requested feature and selected to never
again show a request for this permission (pre API 30) or the user denied
permissions for a second time (API 30 and higher).
The user may still change the permission status in the settings.</p>
<p><em>On iOS:</em>
If the user has denied acces to the requested feature.
The user may still change the permission status in the settings</p>



## Implementation

```dart
Future<bool> get isPermanentlyDenied async =>
    (await this).isPermanentlyDenied;
```








