# music-organizer
python scripts to download music from youtube to mp3 and organize into nice folders

## Software dependencies
- Download youtube videos to mp3: youtube-dl, ffprobe, ffmpeg
- Rename/organize videos: Python >=3.6 (anything that runs .ipynb is fine, [google colab](https://colab.research.google.com/notebooks/intro.ipynb?utm_source=scs-index) should work)

### Install dependencies on Debian:
> sudo apt install youtube-dl ffprobe ffmpeg

## How to use

Steps:
- Get the URL of a youtube video (or playlist) to download
- Use the example scripts in Downloader.ipynb to download the associated mp3 file(s)
- Use the scripts in Organizer.ipynb to modify/shorten the names of large groups of files