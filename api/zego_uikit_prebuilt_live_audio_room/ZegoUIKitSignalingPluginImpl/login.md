


# login method








Future&lt;bool> login
({required String id, required String name})





<p>login</p>



## Implementation

```dart
Future<bool> login({
  required String id,
  required String name,
}) async {
  return ZegoSignalingPluginCore.shared.login(id, name);
}
```







