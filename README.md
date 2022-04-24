# scoop-alts

[![Tests](https://github.com/qwerty12/scoop-alts/actions/workflows/ci.yml/badge.svg)](https://github.com/qwerty12/scoop-alts/actions/workflows/ci.yml) [![Excavator](https://github.com/qwerty12/scoop-alts/actions/workflows/excavator.yml/badge.svg)](https://github.com/qwerty12/scoop-alts/actions/workflows/excavator.yml)

Bucket for [Scoop](https://scoop.sh), the Windows command-line installer.

This, not aiming to be extensive in the slightest, carries manifests bourne out of a personal need:

* [yt-dlp's `ffmpeg` build](https://github.com/yt-dlp/FFmpeg-Builds)

* [shinchiro's nightly `mpv` build](https://github.com/shinchiro/mpv-winbuild-cmake)

* In theory, [the very latest version of SABnzbd](https://github.com/sabnzbd/sabnzbd/releases), whether it be a release, or a beta or an RC.

Thanks to the original authors of the manifests from the default Scoop buckets I copied these from.

How do I install these manifests?
---------------------------------

To add this bucket, run `scoop bucket add scoop-alts https://github.com/qwerty12/scoop-alts`. To install, do `scoop install scoop-alts/<manifest>`.
