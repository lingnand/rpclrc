# rpclrc

rpclrc is a command line script for displaying lyrics of the song being played in [RPD][RPD].

It downloads the lyrics using `lrcdown` as included in the repo. `lrcdown` retrieves lyrics from [http://www.lrc123.com](http://www.lrc123.com).

## Dependencies

* [RPD][RPD]
* [RPC](https://github.com/lynnard/RPC): for parsing the information from [RPD][RPD]

## Usage

1. download the two scripts and put them somewhere reachable from shell
2. launch `rpclrc`
3. it will now download the lyrics for the currently playing song to `~/Music/artist/title.lrc` (if not found) and display the lyrics line by line synchronously (using the timing information in `.lrc`)

[RPD]: http://rpd.lynnard.tk
