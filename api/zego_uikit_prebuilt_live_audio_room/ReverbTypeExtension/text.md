


# text property









String text
  







## Implementation

```dart
String get text {
  final mapValues = {
    ReverbType.none: 'None',
    ReverbType.ktv: 'Karaoke',
    ReverbType.hall: 'Hall',
    ReverbType.concert: 'Concert',
    ReverbType.rock: 'Rock',
    ReverbType.smallRoom: 'Small room',
    ReverbType.largeRoom: 'Large room',
    ReverbType.valley: 'Valley',
    ReverbType.recordingStudio: 'Recording studio',
    ReverbType.basement: 'Basement',
    ReverbType.popular: 'Pop',
    ReverbType.gramophone: 'Gramophone',
  };

  return mapValues[this]!;
}
```








