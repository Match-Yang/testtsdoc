


# isRestricted property









Future&lt;bool> isRestricted
  




<p>If the OS denied this permission. The user cannot change the status,
possibly due to active restrictions such as parental controls being in
place.
<em>Only supported on iOS.</em></p>



## Implementation

```dart
Future<bool> get isRestricted => status.isRestricted;
```








