# Music
A semi-advanced music player that supports any audio file your browser does. The premise is simple: select a file and listen.

[![screenshot](https://i.exerinity.com/lEhoh76L72.png)](https://i.exerinity.com/lEhoh76L72.png)

## Features / cool stuff about it
- Play, pause, and restart audio (obviously)
- No bulky frameworks - pure hand-crafted JS and HTML
- Supports whatever your browser does
- Spread out design: two panels, one for the player and one for the lyrics
- Metadata and lyrics support using [**JSMediaTags**](https://github.com/aadsm/jsmediatags) and **LRCLIB** [(website)](https://lrclib.net) - [(GitHub)](https://github.com/tranxuanthang/lrclib)
- Three visualizers: waveform, spectrum and circular + an off mode with a DVD screensaver-like effect
- Relatively lightweight
- Hotkeys:
### Hotkeys
- **Space**: Toggle playback (Play/Pause)
- **Arrow Left**: Seek backward 10 seconds
- **Shift + Arrow Left**: Seek backward 1 second
- **Arrow Right**: Seek forward 10 seconds
- **Shift + Arrow Right**: Seek forward 1 second
- **Arrow Up**: Increase volume by 2%
- **Arrow Down**: Decrease volume by 2%
- **L**: Toggle loop

## Why?
Consolidating some of my previous player-related projects into one with some more on the side. There is no true reason for this to exist - however, there is also no true reason for you to use it, right?

## Known issues
- Some formats do not load metadata

## Roadmap
- More visualizers
- Ability to control lyrics: an offset (in case a malformed entry is loaded), custom querying, or load your own .srt / .lrc / .vtt / whatever file
- Support mobile better, in a way
- Custom hotkeys
- The app to remember your settings

**If you want to help make these possible, feel free to contribute!**

## License
This application is licensed under the GNU GPL v3 - see the [LICENSE](LICENSE) file for more info.

## Installation
If you want to play around with the code or use it offline, fork this repository or simply download it.

There are no install steps - just run `py -m http.server 80` in its folder - or however you do web servers.

## Mirrors
- https://music.exerinity.com
- https://mus.ex3.icu
- https://sparkfire298.xyz (using my previous username domain for this now)

All of these are identical, just Cloudflare Pages custom domains. What they point to does not differ. 

You can also see the latest Pages build URL by checking the checks tab of the latest commit. The base URL is https://music-517.pages.dev/.