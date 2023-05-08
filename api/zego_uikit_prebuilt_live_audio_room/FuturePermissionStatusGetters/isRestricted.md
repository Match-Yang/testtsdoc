


# isRestricted property









Future&lt;bool> isRestricted
  




<p>If the OS denied access to the requested feature. The user cannot change
this app's status, possibly due to active restrictions such as parental
controls being in place.
<em>Only supported on iOS.</em></p>



## Implementation

```dart
Future<bool> get isRestricted async => (await this).isRestricted;
```








