Needs the [WAV Player application](https://github.com/flipperdevices/flipperzero-firmware/tree/zlo/wav-player/applications/wav_player) compiled into firmware. Original code from [Zlo](https://github.com/flipperdevices/flipperzero-firmware/tree/zlo/wav-player) and initial files provided by [RogueMaster](https://github.com/RogueMaster).

Create a wav_player folder in the root of your SD card. You'll need **8-bit, 2 channel, unsigned WAV files** (try [Audacity](https://www.audacityteam.org/) for conversion.)

WAV Player is very particular about the format. WavPlayer needs BitExact, NO headers, 48k PCM, unsigned, 2 channel, 8-bit stereo. Example:

`Input #0, wav, from '.\rickroll.wav':`<br>
`  Duration: 00:02:03.38, bitrate: 768 kb/s`<br>
`    Stream #0:0: Audio: pcm_u8 ([1][0][0][0] / 0x0001), 48000 Hz, stereo, u8, 768 kb/s`

To produce a compatible file, you can also use [FFmpeg](https://ffmpeg.org/):<br>
`ffmpeg -i .\input.mp3 -c:a pcm_u8 -fflags +bitexact -flags:a +bitexact -ac 2 -ar 48k output.wav`

![WAV_Player](https://user-images.githubusercontent.com/57457139/218230626-8f8e2ad7-f2d5-493d-a2ff-5876ad83d979.PNG)
[More files and info from Loopy The Slayer Fan Girl here](https://github.com/LoopyTheSlayerFanGirl/flipper-wav-songs)!

## Fixes from Unleashed (and likely its forks.)
Unleashed has fixed the above stated issues with tempo and pitch so you no longer need to make adjustments.<br>
You're also free to use 44.1k OR 48k PCM. ([Fixed WAV Player source here](https://github.com/LTVA1/wav_player).)

