


# noSuchMethod method








dynamic noSuchMethod
(Invocation invocation)

_<span class="feature">inherited</span>_



<p>Invoked when a non-existent method or property is accessed.</p>
<p>A dynamic member invocation can attempt to call a member which
doesn't exist on the receiving object. Example:</p>
<pre class="language-dart"><code class="language-dart">dynamic object = 1;
object.add(42); // Statically allowed, run-time error
</code></pre>
<p>This invalid code will invoke the <code>noSuchMethod</code> method
of the integer <code>1</code> with an <code>Invocation</code> representing the
<code>.add(42)</code> call and arguments (which then throws).</p>
<p>Classes can override <a href="../../zego_uikit_prebuilt_live_audio_room/ZIMMediaFileType/noSuchMethod.md">noSuchMethod</a> to provide custom behavior
for such invalid dynamic invocations.</p>
<p>A class with a non-default <a href="../../zego_uikit_prebuilt_live_audio_room/ZIMMediaFileType/noSuchMethod.md">noSuchMethod</a> invocation can also
omit implementations for members of its interface.
Example:</p>
<pre class="language-dart"><code class="language-dart">class MockList&lt;T&gt; implements List&lt;T&gt; {
  noSuchMethod(Invocation invocation) {
    log(invocation);
    super.noSuchMethod(invocation); // Will throw.
  }
}
void main() {
  MockList().add(42);
}
</code></pre>
<p>This code has no compile-time warnings or errors even though
the <code>MockList</code> class has no concrete implementation of
any of the <code>List</code> interface methods.
Calls to <code>List</code> methods are forwarded to <code>noSuchMethod</code>,
so this code will <code>log</code> an invocation similar to
<code>Invocation.method(#add, [42])</code> and then throw.</p>
<p>If a value is returned from <code>noSuchMethod</code>,
it becomes the result of the original invocation.
If the value is not of a type that can be returned by the original
invocation, a type error occurs at the invocation.</p>
<p>The default behavior is to throw a <code>NoSuchMethodError</code>.</p>



## Implementation

```dart
@pragma("vm:entry-point")
@pragma("wasm:entry-point")
external dynamic noSuchMethod(Invocation invocation);
```







