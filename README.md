# PitchPerfect
The Pitch Perfect app is the result of the "Intro to iOS App Development with Swift" lesson as part of Udacity's iOS Developer Nanodegree course.

The App allows users to record a sound using the device’s microphone. It then allows users to play the recorded sound back with six different sound modulations: chipmunk, Darth Vader, slow, fast, reverb and echo.

<img width="295" alt="screenshot 2018-10-12 at 15 25 29" src="https://user-images.githubusercontent.com/28652344/46875406-8e3fcd00-ce33-11e8-981c-1673ad9ad877.png"> <img width="297" alt="screenshot 2018-10-12 at 15 28 11" src="https://user-images.githubusercontent.com/28652344/46875418-9435ae00-ce33-11e8-9c68-61d414c7f460.png"> <img width="297" alt="screenshot 2018-10-12 at 15 26 53" src="https://user-images.githubusercontent.com/28652344/46875424-9861cb80-ce33-11e8-8c0a-977c2f2935f3.png">

## Implementation

Pitch Perfect has two Scenes:

- RecordSoundsViewController : consists a record button with a microphone image. Tapping this microphone button starts an audio recording session and presents a stop button. When the stop button is clicked, the app completes recording and then shows the PlaySoundViewController.
- PlaySoundsViewController : contains six buttons containing images related to the sound effect.  The user has the option to play the recorded sound file with different each of the effects.

The application supports both orientations.  The app also uses code from `AVFoundation` to record sounds from the microphone `(AVAudioRecorder)` and play recorded audio with effects `(AVAudioPlayer, AVAudioEngine)`.

## Requirements

- Xcode 8 Above
- Swift 3.0
