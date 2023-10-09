Dymaxion
========

A Dymaxion/Fuller map projection, originally created by [Eric Gabba](https://commons.wikimedia.org/wiki/User:Sting) and found [on Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Fuller_projection.svg).

![earth unfolded](./Fuller_projection.svg)

I'm editing colors manually and using git to track my changes.

I may put it on a custom-printed shirt.


Turn it into a shirt
====================

To turn this into a shirt using a print-on-demand service like [Printful](https://www.printful.com/design-maker), you may need to turn the SVG into a PNG. You can do that with `rsvg-convert` as explained in [this Superuser post](https://superuser.com/a/723031/37690):

```bash
brew install librsvg
rsvg-convert -w 20000 fuller.svg > fuller.png
```
