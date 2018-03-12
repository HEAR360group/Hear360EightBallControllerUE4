# Hear360 EightBall Controller

*[Unreal Engine plugin] Hear360 EightBall audio plugin and integration*

## Introduction

This plugin renders omni-binaural audio sources into stereo with head tracking. The audio sources are 4 stereo local audio files of 4 different perspective. (front, left, back, right)

## Usage

1. Download or clone this repository into your Plugins/ folder
1. In the editor, go to Edit menu > Plugins and make sure that this plugins are enabled; restart your editor if asked to
1. Locate the `Hear360EightBallAudioController` class in the class browser (the panel on the left) and drop an instance to your level
1. Select the instance just dropped, in `Details`->`Hear360EightBallAudioController(self)`->`DefaultSceneRoot (Inherited)`, set sound for `FrontPlayer`, `LeftPlayer`, `BackPlayer` and `RightPlayer`.
1. Select `Details`->`Hear360EightBallAudioController(self)` node, set `Auto Play` and `Debug` if necessary.
1. `Play()` and `IsPlaying()` methods are accessible by other blueprints.

### UE versions

The plugin is created using UE 4.18.
