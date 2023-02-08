# vimeo_player_flutter plugin

vimeo_player_flutter plugin provides vimeo player Flutter widget based on the webview_flutter plugin.

## Getting Started

Add this to your package's `pubspec.yaml` file:

```yaml
dependencies:
  vimeo_player_flutter: ^0.0.3+6
```

## Usage

Then you just have to import the package with

```dart
import 'package:vimeo_player_flutter/vimeo_player_flutter.dart';
```

## Example

```dart
    Center(
        child: Column(
            children: [
            Container(
                height: 250,
                child: VimeoPlayer(
                videoId: videoId,
                // you can add other parameters
                ),
            ),
            ],
        ),
    ),
```

## Parameters

```dart
  final bool loopVideo; // video loop
  final bool autoPlay; // video autoplay
  final bool showControls; // show player controls
  final bool showSocialIcons; // show social icons
```


## Issues

Please feel free to [let me know any issue](https://github.com/GioRey/vimeo_player/issues) regarding to this plugin.
