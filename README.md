# music

Search YouTube from the terminal, choose a result with fzf, and play the audio in mpv.

```sh
music daft punk around the world   # search, pick, play
music https://youtu.be/...          # play a URL directly
```

Requires zsh, [mpv](https://mpv.io), [yt-dlp](https://github.com/yt-dlp/yt-dlp), and [fzf](https://github.com/junegunn/fzf):

```sh
brew install mpv yt-dlp fzf
cp music ~/.local/bin/ && chmod +x ~/.local/bin/music
```

While it plays: Space/p pause, q quit, Left/Right seek, 9/0 volume, [/] speed.
