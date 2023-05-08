


# setNetWorkResourceMaxCache method








Future&lt;void> setNetWorkResourceMaxCache
(int time, int size)





<p>Set the maximum cache duration and cache data size of web materials.</p>
<p>The setting must be called before loading the resource, and it will take effect during the entire life cycle of the media player.
Time and size are not allowed to be 0 at the same time. The SDK internal default time is 5000, and the size is 15<em>1024</em>1024 byte.When one of time and size reaches the set value first, the cache will stop.</p>
<ul>
<li><code>time</code> The maximum length of the cache time, in ms, the SDK internal default is 5000; the effective value is greater than or equal to 2000; if you fill in 0, it means no limit.</li>
<li><code>size</code> The maximum size of the cache, the unit is byte, the internal default size of the SDK is 15<em>1024</em>1024 byte; the effective value is greater than or equal to 5000000, if you fill in 0, it means no limit.</li>
</ul>



## Implementation

```dart
Future<void> setNetWorkResourceMaxCache(int time, int size);
```







