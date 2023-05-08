


# logConfig property







**Annotations**

- @Deprecated(&#39;This property has been deprecated since version 2.3.0, please use the [setLogConfig] function instead.&#39;)
[ZegoLogConfig](../../zego_uikit_prebuilt_live_audio_room/ZegoLogConfig-class.md)? ~~logConfig~~
  
_<span class="feature">read / write</span>_



<p>Log configuration, if not set, use the default configuration. It must be set before calling <code>createEngine</code> to take effect. If it is set after <code>createEngine</code>, it will take effect at the next <code>createEngine</code> after <code>destroyEngine</code>.</p>



## Implementation

```dart
@Deprecated(
    'This property has been deprecated since version 2.3.0, please use the [setLogConfig] function instead.')
ZegoLogConfig? logConfig;
```







