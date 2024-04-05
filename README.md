# Unofficial Snes9x for Windows ARM64
*Snes9x - Portable Super Nintendo Entertainment System (TM) emulator*

This a project for unofficial builds of the Snes9x project, supporting Windows ARM64

## Changes
* ARM64 target platform support
* Switch to using latest DirectX SDK
* Remove DirectDraw support from compilation

## Known Issues
* Moving away from XAudio2 2.7 drops support for `IXAudio2::GetDeviceCount()` or `IXAudio2::GetDeviceDetails()`. Need to adjust enumerating audio devices. Workaround is to use WaveOut sound driver in settings.

## Test Devices
* Samsung Galaxy Go (Snapdragon 7c Gen 2)
* Dell Inspiron 3420 (Snapdragon 8cx Gen 2)
* Lenovo x13s (Snapdragon 8cx Gen 3)

## Screenshots
![snes9x-sound-settings-arm64](https://github.com/tordona/snes9x/assets/1671976/1b410aa3-becc-4622-93cf-7d7162a29bf3)

![snes9x-super-offroad-arm64](https://github.com/tordona/snes9x/assets/1671976/a46ae186-8c32-4c7d-afcd-6a5f7cd80bc5)

### References
https://walbourn.github.io/xaudio2-and-windows-8/
