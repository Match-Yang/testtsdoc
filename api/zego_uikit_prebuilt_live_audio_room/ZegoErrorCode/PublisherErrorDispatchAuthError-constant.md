


# PublisherErrorDispatchAuthError constant







int const PublisherErrorDispatchAuthError
  




<p>Description: Push-pull flow authentication is incorrect. <br>Caution: An <code>appSign</code> error was passed when creating the engine, or a Token error or timeout was passed when logging into the room. <br>Solutions: Pass the correct <code>Token</code> upon login, or invoke <code>renewToken</code> when recive <code>onRoomTokenWillExpire</code> callback.</p>



## Implementation

```dart
static const int PublisherErrorDispatchAuthError = 1003072;
```







