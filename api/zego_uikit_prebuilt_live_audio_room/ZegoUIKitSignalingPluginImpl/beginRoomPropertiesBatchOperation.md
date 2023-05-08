


# beginRoomPropertiesBatchOperation method








void beginRoomPropertiesBatchOperation
({required String roomID, bool isDeleteAfterOwnerLeft = false, bool isForce = false, bool isUpdateOwner = false})

_<span class="feature">inherited</span>_



<p>begin room properties in batch operation</p>



## Implementation

```dart
void beginRoomPropertiesBatchOperation({
  required String roomID,
  bool isDeleteAfterOwnerLeft = false,
  bool isForce = false,
  bool isUpdateOwner = false,
}) {
  ZegoPluginAdapter().signalingPlugin!.beginRoomPropertiesBatchOperation(
        roomID: roomID,
        isForce: isForce,
        isDeleteAfterOwnerLeft: isDeleteAfterOwnerLeft,
        isUpdateOwner: isUpdateOwner,
      );
}
```







