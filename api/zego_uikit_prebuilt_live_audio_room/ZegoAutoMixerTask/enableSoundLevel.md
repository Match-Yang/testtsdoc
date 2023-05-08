


# enableSoundLevel property







bool enableSoundLevel
  
_<span class="feature">read / write</span>_



<p>Enable or disable sound level callback for the task. If enabled, then the remote player can get the sound level of every stream in the inputlist by <code>onAutoMixerSoundLevelUpdate</code> callback.Description: Enable or disable sound level callback for the task.If enabled, then the remote player can get the sound level of every stream in the inputlist by <code>onAutoMixerSoundLevelUpdate</code> callback.Use cases: This parameter needs to be configured if user need the sound level information of every stream when an auto stream mixing task started.Required: No.Default value: <code>false</code>.Recommended value: Set this parameter based on requirements.</p>



## Implementation

```dart
bool enableSoundLevel;
```







