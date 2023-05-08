


# shouldShowRequestRationale property









Future&lt;bool> shouldShowRequestRationale
  




<p>If you should show a rationale for requesting permission.</p>
<p>This is only implemented on Android, calling this on iOS always returns
<code>false</code>.</p>



## Implementation

```dart
Future<bool> get shouldShowRequestRationale async {
  if (defaultTargetPlatform != TargetPlatform.android) {
    return false;
  }

  return _handler.shouldShowRequestPermissionRationale(this);
}
```








