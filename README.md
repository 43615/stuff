# stuff
Things I made for myself that others may find useful.
- `usde4.klc`: Microsoft Keyboard Layout Creator source file of my custom layout. Base layer is unaltered QWERTY, AltGr(+Shift) contains things like German letters, subscript/superscript numbers and other useful special characters.
- `OctoNarrow.ttf`: Small bitmap font, 8 pixels tall, variable width (as narrow as possible). Covers ASCII + a few other characters.
- `screentest.png`: Test image for modern digital 16:9 displays. Purpose of features:
  - Large black circle and perimeter squares: Aspect ratio, crop/overscan
  - Color sectors: Balance/bias, maximum saturation (image is effectively 1 bpc)
  - Checkerboard pattern squares: The highest one where distinct alternating pixels can be seen (use a magnifying glass!) is the true resolution of the display. Non-listed resolutions require non-integer downscaling from 8K and won't be accurate. Might also be off depending on the renderer.
