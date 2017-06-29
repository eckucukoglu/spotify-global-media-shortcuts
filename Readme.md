# spotify global media shortcuts

Command line control for spotify. Just use **pp** for Play/Pause, **p** for Previous song, **n** for Next song, **s** for Stop.

Spotify linux client accepts [MPRIS](https://specifications.freedesktop.org/mpris-spec/latest/), Media Player Remote Interfacing Specification, this scripts use this communication-interface.
## Commands

* ```pp```: Play or Pause current song.
* ```s```: Stop.
* ```p```: Previous (one time).
  * ```p #times```: Previous #times.
* ```n```: Next (one time).
  * ```n #times```: Next #times.

## Installation:
```
$ git clone https://github.com/eckucukoglu/spotify-global-media-shortcuts.git
$ cd spotify-global-media-shortcuts.git
$ chmod +x install
$ sudo ./install
```
* Uninstall:

```
$ sudo ./install -u
```

### References
[ref1](https://www.kubuntuforums.net/showthread.php?t=58197)
