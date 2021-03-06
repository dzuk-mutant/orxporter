# Formats

### Out of the box support:

- `svg` SVG
- `png` PNG

### Requires extra software to install:

- `svgo` Optimised SVG (requires [svgcleaner]())
- `pngc` Crushed PNG (requires [oxipng]())
- `webp` Lossless WebP (requires [cwebp]())
- `avif` Lossless AVIF (requires [go-avif]())
- `flif` FLIF (requires [flif]())

Crushed PNGs and Optimised SVGs are the same formats as PNG and SVG, but their data is arranged in such a way to create a smaller file size, they require an extra processing stage, and they need the dependencies listed.

When choosing raster images (any format but `svg` and `svgo`), you have to add a size as well. you do this by adding a hyphen followed by the square size in pixels.

eg.

```
flif-32
avif-128
webp-512
pngc-60
```
