


# getVersion method








Future&lt;String> getVersion
()





<p>Gets the SDK's version number.</p>
<p>Available since: 1.1.0
Description: If you encounter an abnormality during the running of the SDK, you can submit the problem, log and other information to the ZEGO technical staff to locate and troubleshoot. Developers can also collect current SDK version information through this API, which is convenient for App operation statistics and related issues.
When to call: Any time.
Restrictions: None.
Caution: None.</p>
<ul>
<li>Returns SDK version.</li>
</ul>



## Implementation

```dart
static Future<String> getVersion() async {
  return await ZegoExpressImpl.getVersion();
}
```







