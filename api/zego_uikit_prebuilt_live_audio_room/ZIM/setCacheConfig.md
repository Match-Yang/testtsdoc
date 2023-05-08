


# setCacheConfig method








dynamic setCacheConfig
([ZIMCacheConfig](../../zego_uikit_prebuilt_live_audio_room/ZIMCacheConfig-class.md) config)





<p>Set cache related configuration.</p>
<p><code>config</code> Log configuration object.
Supported version: 2.1.5 and above.</p>
<p>Detailed description: Example Set the SDK cache file path. Because the SDK has a default path, it is generally not recommended that you set your own path unless there is a strong need to do so.</p>
<p>Default value:Android：/storage/Android/data/packageName/files/ZIMCaches
iOS：~/Library/Caches/ZIMCaches
macOS：（sandbox）~/Library/Containers/<code>Bundle ID</code>/Data/Library/Caches/ZIMCaches / ~/Library/Caches/ZIMCaches
Windows：C:\Users[Your UserName]\AppData[App Name]ZEGO.SDK\ZIMCaches</p>
<p>Call timing: It must be called before <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/create.md">create</a>.</p>
<p>Note: If the developer calls after <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/create.md">create</a>, the SDK saves the configuration until it takes effect the next time <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/create.md">create</a> is invoked.</p>
<p>Related callbacks: In addition to getting the login result in the callback parameter, the developer will also receive the <code>onConnectionStateChanged</code> callback during the login request and after the login is successful/failed to determine the current user's login status.</p>
<p>Life cycle: Set before calling <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/create.md">create</a> and takes effect when calling <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/create.md">create</a>. If the developer does not set the new logging configuration the next time <a href="../../zego_uikit_prebuilt_live_audio_room/ZIM/create.md">create</a> is created, the previous configuration will still take effect.</p>
<p>Platform difference: The default path varies with platforms. Please refer to the default value.</p>
<p><code>config</code> Cache configuration object.</p>



## Implementation

```dart
/// Supported version: 2.1.5 and above.
///
/// Detailed description: Example Set the SDK cache file path. Because the SDK has a default path, it is generally not recommended that you set your own path unless there is a strong need to do so.
///
/// Default value:Android：/storage/Android/data/packageName/files/ZIMCaches
/// iOS：~/Library/Caches/ZIMCaches
/// macOS：（sandbox）~/Library/Containers/[Bundle ID]/Data/Library/Caches/ZIMCaches / ~/Library/Caches/ZIMCaches
/// Windows：C:\Users\[Your UserName]\AppData\[App Name]ZEGO.SDK\ZIMCaches
///
/// Call timing: It must be called before [create].
///
/// Note: If the developer calls after [create], the SDK saves the configuration until it takes effect the next time [create] is invoked.
///
/// Related callbacks: In addition to getting the login result in the callback parameter, the developer will also receive the [onConnectionStateChanged] callback during the login request and after the login is successful/failed to determine the current user's login status.
///
/// Life cycle: Set before calling [create] and takes effect when calling [create]. If the developer does not set the new logging configuration the next time [create] is created, the previous configuration will still take effect.
///
/// Platform difference: The default path varies with platforms. Please refer to the default value.
///
/// [config] Cache configuration object.
static setCacheConfig(ZIMCacheConfig config) {
  ZIMManager.setCacheConfig(config);
}
```







