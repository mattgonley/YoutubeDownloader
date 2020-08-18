## YoutubeDowloader
Python script to download YouTube playlists

## Author
* Matt Gonley

## Details
* Download any size playlist
* downloads as mp4 files with only the audio

## Required Software
This program makes use of selenium webdrivers, and in particular their firefox webdriver.
Fot that to function, a software driver needs to be installed.
It can de downloaded from: github.com/mozilla/geckodriver/releases/latest
When installed, the file needs to be added to the path.


## Installation
**NOTE**: Python 3 is required.
```console
# clone the repo
$ git clone https://github.com/mattgonley/YoutubeDowloader.git

# change the working directory to YoutubeDownloader
$ cd YoutubeDownloader

# install python3 if it is not already installed

# install the requirements
$ python install.py
```

## Usage
For use with the GUI (Graphical User Interface):
```console
$ python -m scr
```
Which will launch the GUI for one to use and interact with.

For use without the GUI:
```console
$ python -m scr [enter link(s) seperated by a space]
```
Example:
```
$ python -m scr www.youtube.com/watch?v=4CdFBfKMAU4 www.youtube.com/watch?v=wzS5-AjJ71E
```
The above example would download the 2 videos specified in the links


## Features
* Download playlist of any size
* Download single video
* The Song(s) will have artist and title label
* Choose download location, and make folder with playlist name for songs their

## Intended Features (Potential future features)
* Convert mp4 files to mp3
* Detail number of videos downloaded out of number in playlist
* Allow to download videos behind sensitivity filter on youtube

## License
* MIT License 

## Warning
Downloading youtube videos is aginst YouTubes Terms of service. As such use of this code carries a risk. This was created for fun, and definitelly not to download youtube videos. If one chooses to use it to download videos, a VPN may not be a bad idea.

##
* If their is features one would like added, feel free to comment and its possible I will add it when I have the time
