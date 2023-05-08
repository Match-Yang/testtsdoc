


# getVersion method








Future&lt;String> getVersion
()





<p>Gets the SDK's version number.</p>
<p>When the SDK is running, the developer finds that it does not match the expected situation and submits the problem and related logs to the ZEGO technical staff for locating. The ZEGO technical staff may need the information of the engine version to assist in locating the problem.
Developers can also collect this information as the version information of the engine used by the app, so that the SDK corresponding to each version of the app on the line.</p>
<p>Available since: 2.1.5.</p>
<p>Description: Get the SDK version.</p>
<p>Use cases:</p>
<ol>
<li>When the SDK is running, the developer finds that it does not match the expected situation and submits the problem and related logs to the ZEGO technical staff for locating. The ZEGO technical staff may need the information of the engine version to assist in locating the problem.</li>
<li>Developers can also collect this information as the version information of the engine used by the app, so that the SDK corresponding to each version of the app on the line.</li>
</ol>
<p>When to call : It can be called at any time.</p>
<p>@return SDK version.</p>



## Implementation

```dart
static Future<String> getVersion() async {
  return await ZIMManager.getVersion();
}
```







