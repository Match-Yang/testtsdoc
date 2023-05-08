


# onDebugError property







(void Function(int errorCode, String funcName, String info)?) onDebugError
  
_<span class="feature">read / write</span>_



<p>The callback for obtaining debugging error information.</p>
<p>Available since: 1.1.0
Description: When the SDK functions are not used correctly, the callback prompts for detailed error information.
Trigger: Notify the developer when an exception occurs in the SDK.
Restrictions: None.
Caution: None.</p>
<ul>
<li><code>errorCode</code> Error code, please refer to the error codes document <a href="https://docs.zegocloud.com/en/5548.html">https://docs.zegocloud.com/en/5548.html</a> for details.</li>
<li><code>funcName</code> Function name.</li>
<li><code>info</code> Detailed error information.</li>
</ul>



## Implementation

```dart
static void Function(int errorCode, String funcName, String info)?
    onDebugError;
```







