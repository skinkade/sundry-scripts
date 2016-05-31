# Clip Fix

Benjamin Schwartz' Nyquist plugin made standalone and parallelized via bash wrapper.

Good for declipping albums which are victims of the loudness war.

Requires the Nyquist interpreter, GNU parallel, and ffmpeg.

```shell
/tmp $ clipfix ~/Music/Clipped_Album/*
/home/you/Music/Clipped_Album/01 - Title.flac
    => /tmp/01 - Title - declipped.flac
...
```
