

# ZegoLiveAudioRoomBackgroundBuilder typedef

    Widget ZegoLiveAudioRoomBackgroundBuilder = Widget Function(BuildContext context, Size size, Map&lt;String, dynamic> extraInfo)

<p>ZegoLiveAudioRoomBackgroundBuilder that is used to build a widget representing the Live Audio Room background.</p>
<p>因为这个方法要求返回一个Widget，所以你可以用任何Widget作为语聊房的背景。比如一段视频、一个GIF动画、一张图片、一个网页等等。
因为这个方法只会在Live Audio Room SDK初始化时调用，如果你需要动态改变背景内容，那么你需要在你返回的Widget内部实现动态修改的逻辑。</p>
<p>The function type takes in three parameters: <code>context</code>, <code>size</code>, and <code>extraInfo</code>.
The <code>context</code> parameter is of type <code>BuildContext</code> and represents the build context of the widget.
The <code>size</code> parameter is of type <code>Size</code> and represents the size of the widget.
The <code>extraInfo</code> parameter is of type <code>Map&lt;String, dynamic&gt;</code> and represents a map of extra information that may be used to customize the widget.</p>

## Implementation

```dart
typedef ZegoLiveAudioRoomBackgroundBuilder = Widget Function(
  BuildContext context,
  Size size,
  Map<String, dynamic> extraInfo,
);
```


