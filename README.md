# ffmpeg-nuget

A nuget package for FFmpeg based on the [official builds](https://ffmpeg.zeranoe.com/builds/).

[![Build status](https://ci.appveyor.com/api/projects/status/vcsn0fpr5s1j6p2y/branch/master?svg=true)](https://ci.appveyor.com/project/mcmtroffaes/ffmpeg-nuget/branch/master)

## Requirements

* [Nuget](https://www.nuget.org/)

## Usage

  * Use ``install.ps1`` to download and extract the relevant FFmpeg dev and shared builds for both 32 bit and 64 bit.
  * Use ``build.ps1`` to regenerate the lib files using Visual Studio 14.0 tools.
  * Use ``nuget pack FFmpeg.Nightly.nuspec`` to create the nuget package.

## License

All the source code is licensed under the conditions of the [MIT license](LICENSE.txt).
