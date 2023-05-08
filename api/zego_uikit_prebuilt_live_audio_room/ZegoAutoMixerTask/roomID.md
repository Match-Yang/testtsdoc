


# roomID property







String roomID
  
_<span class="feature">read / write</span>_



<p>The roomID of the auto mixer task.Description: Auto stream mixing task id.Use cases: User need to set this parameter when initiating an auto stream mixing task.Required: Yes.Recommended value: Set this parameter based on requirements.Value range: A string up to 128 bytes.Caution: Only support numbers, English characters and '~', '!', '@', '#', '$', '%', '^', '&amp;', '*', '(', ')', '_', '+', '=', '-', '`', ';', '’', ',', '.', '&lt;', '&gt;', '/', ''.If you need to communicate with the Web SDK, please do not use '%'.</p>



## Implementation

```dart
String roomID;
```







