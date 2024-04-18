# Download YT Audios & Transcriptions

# _A brief description_
Hey there! 

So, I'm a huge fan of Ted-Ed videos, I definitively think they're a greate way to discover new topics, get an initial idea from a science or just for listening a history. So, why am I creating this project?

If you used to travel by subway, you may be notice there's a terrible conectivity underground, so you can't watch your videos in your way to school, work or other. You can just simply download the audio, and maybe if you're amazing listening to a second language you can enjoy the full audio. But that's not my case, so I'm doing a code that actually can download the audio and the transcription.

To do this project I'm using PyTube, in my little reacher about how to do this project I found it, it's very easy to use, and it can get you the audio of a video or a hole playlist. And the rest of the project is just save the audio and the transcription in a .txt.

If you're reading this expecting to watch a lot of math, there's ln 1 of math in this project:( 

## Installation

In order to use this projects, you only need to download the PyTube library as:
```bash
pip install pytube
```
There's a certain problem, due to the library has a conflict with the subtitles, this is because YT used to change the subtitle format very often. So what does that mean? It's means you must change a little the library, but don't worry, it's very easy to do and I'll let you the exactly lines you must modify:
```bash
https://github.com/pytube/pytube/issues/1477
```
These modifications must be done in the caption.py file, you can find this file in the folder 
```bash
C:\Users\User\anaconda3\envs\PyTube\Lib\site-packages\pytube
```
If you're using Conda.

## Usage
After installing the library, it's done! Select the code acording to your purposes. The first code allows you to download the audio from a video and its transcription, in this code you must modify the second block with your YT link and the folder path where you want the files be saved. 

The Playlist code it's more easy to use, when you execute it, it'll ask you for the playlist URL and the folder path, also I'll give you the option to get or not the transcription. 

I've done this project using Jupyter Notebook 'cause I think it's the most didactic environment for this kind of projects. 

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## What's Next?
I've done this project so I can listening TED-Ed videos, so I'd like a place where I can storage this. The next project is use Telegram as a Cloud!
