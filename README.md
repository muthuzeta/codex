# GifInspiredAndroid

A minimal Android app that reproduces the attached Dribbble concept by loading and looping the provided GIF URL.

## What this includes
- Jetpack Compose single-screen app.
- Coil image loading with GIF decoder support.
- Full-screen centered animation playback.

## GIF source
`https://cdn.dribbble.com/userupload/41960666/file/original-d3690b9614729acc574cfffdcc0db257.gif`

## Run locally
1. Open this folder in Android Studio (Giraffe+).
2. Let Gradle sync.
3. Run on an emulator/device (API 26+).

## Notes
If you want this to be a *native recreation* (vector/Lottie/Compose animation) rather than displaying the GIF directly, the next step is to break the motion into keyframes and rebuild each layer in Compose.
