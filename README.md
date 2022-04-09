# scoop-alts

[![Tests](https://github.com/qwerty12/scoop-alts/actions/workflows/ci.yml/badge.svg)](https://github.com/qwerty12/scoop-alts/actions/workflows/ci.yml) [![Excavator](https://github.com/qwerty12/scoop-alts/actions/workflows/excavator.yml/badge.svg)](https://github.com/qwerty12/scoop-alts/actions/workflows/excavator.yml)

Bucket for [Scoop](https://scoop.sh), the Windows command-line installer.

This, not aiming to be extensive in the slightest, carries three manifests made for my needs:

* [yt-dlp's `ffmpeg` build](https://github.com/yt-dlp/FFmpeg-Builds)

* [zhongfly's nightly `mpv` build](https://github.com/zhongfly/mpv-winbuild)

Thanks to the original authors of the manifests from the default Scoop buckets I copied these from.

How do I install these manifests?
---------------------------------

To add this bucket, run `scoop bucket add scoop-alts https://github.com/qwerty12/scoop-alts`. To install, do `scoop install <manifest>`.
