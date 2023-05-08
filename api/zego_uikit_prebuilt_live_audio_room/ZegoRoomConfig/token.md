


# token property







String token
  
_<span class="feature">read / write</span>_



<p>The token issued by the developer's business server is used to ensure security. For the generation rules, please refer to <a href="https://doc-zh.zego.im/article/10360">Using Token Authentication</a>, the default is an empty string, that is, no authentication. In versions 2.17.0 and above, if appSign is not passed in when calling the <code>createEngine</code> API to create an engine, or if appSign is empty, this parameter must be set for authentication when logging in to a room.</p>



## Implementation

```dart
String token;
```







