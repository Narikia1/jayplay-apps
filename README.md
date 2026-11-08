# JayPlay downloads

JayPlay plays video, music and audiobooks in almost any format on Mac, Windows, iPhone, iPad and Android.
It is part of the JayApps family by Narikia.

**Get it at [jayplay.narikia.com](https://jayplay.narikia.com).** The website always links to the latest release here.

| Device | File |
| --- | --- |
| Mac (macOS 14 or later) | `JayPlay-mac.dmg`, signed with an Apple Developer ID and notarized by Apple |
| Windows 10 or 11, 64-bit | `JayPlay-Setup.exe` |
| Android 8 or later | `JayPlay-android.apk` |
| iPhone and iPad | Coming to the App Store |

`SHA256SUMS.txt` in each release lets you check a download is the file we published:
`shasum -a 256 -c SHA256SUMS.txt` on Mac, or `Get-FileHash JayPlay-Setup.exe` on Windows.

## Open source inside

JayPlay plays media through [mpv](https://mpv.io) and [FFmpeg](https://ffmpeg.org), built as LGPL libraries
that stay separate and replaceable. The full list of projects and licences is at
[jayplay.narikia.com/en/licences](https://jayplay.narikia.com/en/licences). For the corresponding source code,
write to it@narikia.com.

## What is in this repository

Only the release workflow and the published files. The Windows workflow builds and tests JayPlay on a real
Windows machine and keeps the installer and its test evidence as artifacts.
