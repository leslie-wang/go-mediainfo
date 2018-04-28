## go-mediainfo

Basic MediaInfo bindings for Go.

## Installing

go get github.com/dwbuiten/go-mediainfo/mediainfo

## To generate timestamp during ffmpeg transcoding
ffmpeg -i <input> -metadata date="UTC 2013-08-08 08:08:08" <output>