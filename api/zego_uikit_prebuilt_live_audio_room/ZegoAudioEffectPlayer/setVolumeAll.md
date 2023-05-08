


# setVolumeAll method








Future&lt;void> setVolumeAll
(int volume)





<p>Set volume for all audio effect. Both the local play volume and the publish volume are set.</p>
<p>Available since: 1.16.0
Description: Set volume for all audio effect. Both the local play volume and the publish volume are set.
When to call: It can be called after <code>createAudioEffectPlayer</code>.
Restrictions: None.</p>
<ul>
<li><code>volume</code> Volume. <br>Value range: The range is 0 ~ 200. <br>Default value: The default is 100.</li>
</ul>



## Implementation

```dart
Future<void> setVolumeAll(int volume);
```







