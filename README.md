# ExoPlayer #

ExoPlayer is an application level media player for Android. It provides an
alternative to Android’s MediaPlayer API for playing audio and video both
locally and over the Internet. ExoPlayer supports features not currently
supported by Android’s MediaPlayer API, including DASH and SmoothStreaming
adaptive playbacks. Unlike the MediaPlayer API, ExoPlayer is easy to customize
and extend, and can be updated through Play Store application updates.

## Documentation ##

* The [developer guide][] provides a wealth of information to help you get
  started.
* The [class reference][] documents the ExoPlayer library classes.
* The [release notes][] document the major changes in each release.

[developer guide]: https://google.github.io/ExoPlayer/guide.html
[class reference]: https://google.github.io/ExoPlayer/doc/reference
[release notes]: https://github.com/google/ExoPlayer/blob/dev-v2/RELEASENOTES.md

## Compilation

Compile by entering the directory for the library project. Run ../gradlew build. An outputs directory will be created which contains library.jar. This can be copied into the libs folder of another Android studio project.

## Modifications

There are two modifications to this lib from the standard version, at the time of writing. The first enables the duration to be set for dynamic length playlists, the second allows normal seeking behaviour for live playlists.
