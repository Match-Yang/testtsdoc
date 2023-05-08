


# background property







Widget? background
  
_<span class="feature">read / write</span>_



<p>语聊房屏幕的背景</p>
<p>你可以用任何Widget作为语聊房的背景。比如一段视频、一个GIF动画、一张图片、一个网页等等。
如果你需要动态改变背景内容，那么你需要在你返回的Widget内部实现动态修改的逻辑。</p>
<pre class="language-dart"><code class="language-dart">
 // eg:
..background = Container(
    width: size.width,
    height: size.height,
    decoration: const BoxDecoration(
      image: DecorationImage(
        fit: BoxFit.fitHeight,
        image: ,
      )));
</code></pre>



## Implementation

```dart
Widget? background;
```







