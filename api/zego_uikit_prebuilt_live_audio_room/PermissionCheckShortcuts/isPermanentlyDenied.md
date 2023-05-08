


# isPermanentlyDenied property









Future&lt;bool> isPermanentlyDenied
  




<p>Returns <code>true</code> when permissions are denied permanently.</p>
<p>When permissions are denied permanently, no new permission dialog will
be showed to the user. Consuming Apps should redirect the user to the
App settings to change permissions.</p>



## Implementation

```dart
Future<bool> get isPermanentlyDenied => status.isPermanentlyDenied;
```








