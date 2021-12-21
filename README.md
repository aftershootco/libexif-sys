# LibExif Rust Bindings

The `libexif-sys` crate provides declarations and linkage for the `libexif` C library. Following the
`*-sys` package conventions, the `libexif-sys` crate does not define higher-level abstractions over
the native `libexif` library functions.

## Dependencies
In order to use the `libexif-sys` crate, you must have the `libexif` library installed.

## Finding Help
Since `libexif-sys` does nothing more than export symbols from the native `libexif` library, the best
source for help is the information already available for the native `libexif`.