# playtxt
YouTube audio stream player...

...that can only play songs from a text file with song names

Pretty useful, if you ask me.

Currently only available for Linux, but probably would work on Windows with minimal modifications.

### Dependencies
[pip] bs4 requests
`pip install bs4 requests`

[pacman] youtube-dl mpv
`sudo pacman -S youtube-dl mpv`

### Installation
`sudo python setup.py install`

Usage: `playtxt.py <file>`

For help, ~~scream~~ `playtxt.py -h` or `playtxt.py --help`

It was cobbled together in an hour, from a StackOverflow question somebody asked.

It basically was already pretty much done before me, but nobody made this, as far as I know, for some reason.

TODO:

Play/pause/skip commands

Volume control

Looping
