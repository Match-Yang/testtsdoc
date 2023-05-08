


# getCacheSize method








Future&lt;int> getCacheSize
()





<p>Get cache size.</p>
<p>Available since: 2.13.0
Description: When using this module, some cache files may be generated, and the size of the cache file can be obtained through this interface.
Use case: Used to display the cache size of the App.
When to call: After initializing the copyrighted music <code>createCopyrightedMusic</code>.</p>
<ul>
<li>Returns cache file size, in byte.</li>
</ul>



## Implementation

```dart
Future<int> getCacheSize();
```







