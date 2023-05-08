


# userInRoomAttributes property







Map&lt;String, String> userInRoomAttributes
  
_<span class="feature">read / write</span>_



<p>设置当前用户在当前加入的语聊房的属性
<code>userAvatarUrl</code>实际使用的也是这个属性，占用了key为avatar的一个属性</p>
<p>For a single user, the sum of all Key-Value pairs must be within 100 bytes and a maximum of 20 pairs can be configured.
Each Key must be within 8 bytes.
Each Value must be within 64 bytes.
如果你希望提高限制上限，请联系技术支持。</p>



## Implementation

```dart
Map<String, String> userInRoomAttributes;
```







