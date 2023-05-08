


# CopyrightedMusicResourceIdUnauthorized constant







int const CopyrightedMusicResourceIdUnauthorized
  




<p>Description: The resource_id unauthorized. <br>Cause: When <code>download</code> is called to download resources, the resource_id is unauthorization. <br>Solutions: Please call the <code>requestSong</code> <code>requestAccompaniment</code> <code>requestAccompanimentClip</code> <code>getMusicByToken</code> function before call <code>load</code> function to load resource.</p>



## Implementation

```dart
static const int CopyrightedMusicResourceIdUnauthorized = 1017018;
```







