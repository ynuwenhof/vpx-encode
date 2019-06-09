# record-screen

Record a movie of your screen

This simple utility records a movie (video only, no audio) of your screen.

It it based entirely on code from [srs](), and has been maintained as an
example application to test the [vpx-encode]() library.

## Installation

This can be installed with:

```sh
cargo install record-screen
```

Don't forget to install `libvpx`.

## Video Format

The video is stored as a WebM file, using the VP9 and Opus codecs.

## Contributing

All contributions are appreciated.

License: MIT
