# m3u8-segmenter

This code  was originally written by Chase Douglas and  John Ferlito.
I made some minor modification for a specific project.
You should rather use the original code: https://github.com/johnf/m3u8-segmenter

## Usage

Some example command lines

    ffmpeg -loglevel quiet  -i big_buck_bunny.ogv -f mpegts - | \
        m3u8-segmenter -i - -d 10 -p tmp/big_buck_bunny -m tmp/big_buck.m3u8 -u http://inodes.org/bigbuck/

