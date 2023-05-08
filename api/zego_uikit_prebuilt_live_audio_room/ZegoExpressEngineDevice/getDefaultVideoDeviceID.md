


# getDefaultVideoDeviceID method








Future&lt;String> getDefaultVideoDeviceID
()





<p>Get the device ID of the default video device.</p>
<p>Only for Windows / macOS / Linux
Note: This function is only available in ZegoExpressVideo SDK!</p>
<ul>
<li>Returns Default video device ID</li>
</ul>



## Implementation

```dart
Future<String> getDefaultVideoDeviceID() async {
  return await ZegoExpressImpl.instance.getDefaultVideoDeviceID();
}
```







