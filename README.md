# youtube-dl/yt-dlp config files

A handful of config files I create for easier use of youtube-dl/yt-dlp. Instead of having to pass different arguments each time, I extracted them to separate config files.

You can always check what each argument does from the official docs of [youtube-dl](https://github.com/ytdl-org/youtube-dl) or [yt-dlp](https://github.com/yt-dlp/yt-dlp).

I personally use yt-dlp fork over youtube-dl because it has fixed some bugs (especially throttling) that I faced in youtube-dl. It also has some nice additional new features and is maintained properly.

### Usage:

Just replace "\*.conf" with the config filename.

```
yt-dlp --config-locations "D:\YOUR CONFIG PATH\youtube-dl *.conf" URL
```

### Note:

- If you want to save files in default location just remove the line that starts with -o.
