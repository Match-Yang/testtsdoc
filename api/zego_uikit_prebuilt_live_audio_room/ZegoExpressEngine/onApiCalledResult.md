


# onApiCalledResult property







(void Function(int errorCode, String funcName, String info)?) onApiCalledResult
  
_<span class="feature">read / write</span>_



<p>Method execution result callback</p>
<p>Available since: 2.3.0
Description: When the monitoring is turned on through <code>setApiCalledCallback</code>, the results of the execution of all methods will be called back through this callback.
Trigger: When the developer calls the SDK method, the execution result of the method is called back.
Restrictions: None.
Caution: It is recommended to monitor and process this callback in the development and testing phases, and turn off the monitoring of this callback after going online.</p>
<ul>
<li><code>errorCode</code> Error code, please refer to the error codes document <a href="https://docs.zegocloud.com/en/5548.html">https://docs.zegocloud.com/en/5548.html</a> for details.</li>
<li><code>funcName</code> Function name.</li>
<li><code>info</code> Detailed error information.</li>
</ul>



## Implementation

```dart
static void Function(int errorCode, String funcName, String info)?
    onApiCalledResult;
```







