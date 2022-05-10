
<h1 align="center">theScreensaver:sparkles:</h1>

#### <p align="center">Quickly create a randomized montage of all your favorite video files!</p>


Shell script that picks a random 9 second interval from a random video file (mkv, mp4, webm, etc) in a directory and appends it to an EDL file.


###### Requirements:
- [`MediaInfo`](https://github.com/MediaArea/MediaInfo) - needed to get the length of video files

        Ubuntu:
        - snap install mediainfo
        - apt install mediainfo
        
        Arch:
        - pacman -S mediainfo

- [`mpv`](https://github.com/mpv-player/mpv) - needed to play the EDL file once created.

        Ubuntu:
        - apt install mpv
        
        Arch:
        - pacman -S mpv


