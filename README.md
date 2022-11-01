# **y**ou**t**ube **v**ideo **d**ownloader

> NOTE: You can do lot more if you directly use youtube-dl. This script only does what suits me.

> NOTE: it requires [youtube-dl](https://github.com/ytdl-org/youtube-dl), [ffmpeg](https://github.com/FFmpeg/FFmpeg), `dialog` to run and uses GNU Core Utilities commands `grep`, `awk` etc.

```
pacman -S dialog youtube-dl ffmpeg
apt install dialog ffmpeg youtube-dl
```

## Installing

For the current user:

```sh
curl https://raw.githubusercontent.com/shivajichalise/ytvd/main/ytvd > ~/usr/local/bin/ytvd && chmod +x ~/usr/local/bin/ytvd
```

Or simply copy the `ytvd` file to a location in your `$PATH` and make it executable.

## Usage

- run `ytvd <youtube-video-link>` or just `ytvd`
- if asked for input give appropriate input

## How it works

it just runs `youtube-dl` and `ffmpeg` behind-the-scenes

## Self-Promotion

Star the repository on [Github](https://github.com/shivajichalise/ytvd)
Follow [shivajichalise](http://shivajichalise.com.np) on [Github](https://github.com/shivajichalise)

## License

This project is licensed under [GPL-3.0](https://www.gnu.org/licenses/gpl-3.0.en.html)
