# tkmaker
tkmaker is bunch of shell code to merge image, audio and subtitle into video. It's based on ffmpeg and ffmpeg-progressbar-cli to show progressbar and ETA as well.

## Install ffmpeg-progress-cli via npm
npm install --global ffmpeg-progressbar-cli

## Copy file tkmaker to /usr/bin
sudo cp tkmaker /usr/bin

## Usage
Example : 
* Merge image, audio and subtitle. (-F | -full | --full): 
```shell
    tkmaker -F -i image.gif -a audio.mp3 -s subtitle.srt
```
* Merge image and audio into video. (-I | -img2vid | --img2vid): 
```shell
    tkmaker -I -i image.gif -a audio.mp3 -s subtitle.srt
```
* For more detail.
```shell
    tkmaker --help
```

## Demo
A lyric video was rendered by tkmaker. [Click here](https://www.youtube.com/watch?v=Q8CjOPsLenY)
