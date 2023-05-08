


# CommonEngineNotCreate constant







int const CommonEngineNotCreate
  




<p>Description: The engine is not initialized and cannot call non-static functions. <br>Cause: Engine not created.<br>Solutions: Please call the <code>createEngine</code> function to create the engine first, and then call the current function.</p>



## Implementation

```dart
static const int CommonEngineNotCreate = 1000001;
```







