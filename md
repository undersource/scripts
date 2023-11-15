#!/bin/sh

yt-dlp -f 'ba' -x --audio-format flac -o "%(title)s.%(ext)s" $1
