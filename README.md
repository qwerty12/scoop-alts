# scoop-alts

[![Tests](https://github.com/qwerty12/scoop-alts/actions/workflows/ci.yml/badge.svg)](https://github.com/qwerty12/scoop-alts/actions/workflows/ci.yml) [![Excavator](https://github.com/qwerty12/scoop-alts/actions/workflows/excavator.yml/badge.svg)](https://github.com/qwerty12/scoop-alts/actions/workflows/excavator.yml)

Bucket for [Scoop](https://scoop.sh), the Windows command-line installer.

This, not aiming to be extensive in the slightest, carries manifests bourne out of a personal need. For example:

* [yt-dlp's `ffmpeg` build](https://github.com/yt-dlp/FFmpeg-Builds)

* [My *modified* nightly `mpv` builds](https://github.com/qwerty12/mpv-winbuild) (nightlies of shinchiro's mpv builds are in the main Scoop buckets)

* [The very latest version of SABnzbd](https://github.com/sabnzbd/sabnzbd/releases), whether it be a release, or a beta or an RC.

How do I install these manifests?
---------------------------------

To add this bucket, run `scoop bucket add scoop-alts https://github.com/qwerty12/scoop-alts`. To install, do `scoop install scoop-alts/<manifest>`.

---------------------------------

<details>

<summary>Thanks to the original authors of the manifests from the default Scoop buckets I copied some of these from:</summary>

* https://raw.githubusercontent.com/ScoopInstaller/Versions/master/bucket/ffmpeg-shared-nightly.json

* https://raw.githubusercontent.com/ScoopInstaller/Extras/master/bucket/jadx.json

* https://raw.githubusercontent.com/ScoopInstaller/Extras/master/bucket/mpv-git.json

* https://raw.githubusercontent.com/ScoopInstaller/Extras/master/bucket/sabnzbd.json

* https://raw.githubusercontent.com/ScoopInstaller/Main/master/bucket/yt-dlp.json

* https://github.com/404NetworkError/scoop-bucket/blob/main/bucket/winsetview-nightly.json

* https://raw.githubusercontent.com/ScoopInstaller/Extras/master/bucket/ungoogled-chromium.json

* https://raw.githubusercontent.com/ScoopInstaller/Extras/master/bucket/googlechrome.json

* https://raw.githubusercontent.com/ScoopInstaller/Extras/master/bucket/fastcopy.json

* https://raw.githubusercontent.com/ScoopInstaller/Extras/master/bucket/vscode.json

* https://raw.githubusercontent.com/ScoopInstaller/Extras/master/bucket/syncthingtray.json

* https://github.com/ScoopInstaller/Nonportable/blob/master/bucket/openhashtab-np.json
</details>
