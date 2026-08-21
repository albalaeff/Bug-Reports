## [Android 16] Disneyland Paris app stops background audio when opened
Device: Xiaomi Redmi 15

## Steps to reproduce:
Preconditions: <br>
1.The Disneyland Paris app is installed.<br>
2.Background audio is playing in another application.<br>

Steps to reproduce:<br>
1.Open a music or podcast application.<br>
2.Start playing any audio.<br>
3.Leave the audio application while the audio continues playing in the background.<br>
4.Launch the Disneyland Paris application.<br>
5.Wait until the home screen is displayed.<br>

## Expected result:
Background audio continues playing because the Disneyland Paris home screen does not contain video, audio, or another feature that visibly requires audio focus

## Actual result:
The Disneyland Paris application stops the audio playback after the homepage is loaded.

## Type:
Functional

## Severity: 
Medium

[View screenshot 1](DisneyAudioBug.mp4)
