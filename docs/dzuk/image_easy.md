# Simple image output method


## Formats (`-F`)

[Check out this doc](image_formats.md) for a list of the supported formats and how to type them.

You can put multiple formats in this flag in a comma-separated list like this:

````
-F svgo-69,flif-420,pngc-666,png-128
````

## Directory and filename structure (`-f`) (optional)

This is a way of fiddling with the way that your output files are named and what folder structure they will be stored in.

[Check out this doc] for the kinds of things you can do.


## Renderer (`-r`) (optional)

This is how PNGs are produced (either standalone or for other formats like WebP and FLIF).
Depending on what you have or install, you can choose:
- inkscape
- imagemagick
- rendersvg

Based on our experiences, we highly recommend rendersvg because it is much faster than the others.
It's also much tidier to use on macOS.
