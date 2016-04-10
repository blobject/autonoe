# autonoe

[agave]: https://github.com/agarick/agave
[ff]: https://fontforge.github.io
[gbdfed]: http://www.math.nmsu.edu/~mleisher/Software/gbdfed/
[license]: https://github.com/agarick/autonoe/blob/master/LICENSE
[xlfd]: http://en.wikipedia.org/wiki/X_logical_font_description
[xorg]: http://www.x.org/wiki/

## get

### download

* [autonoe, version 003](https://github.com/agarick/autonoe/raw/master/autonoe-003.tar.gz)

### files

The download link gets you a tarballed *autonoe*. It contains a `.bdf`, a `.sfd`, and a `.pcf.gz` file. The first two are "source" files that you can modify and compile to your liking. The last is the actual font file that you'll want to install, assuming you're in an [X.Org][xorg] environment.

## about

*autonoe* is a fixed-width, 7x14, bold-only, unicode, bitmap typeface.

Furthermore, the font ...:

* Is under the [MIT X license][license].
* Has an [xlfd][xlfd] of `-agaric-autonoe-bold-r-normal--14-100-96-96-m-70-iso10646-1`.
* Is basically *fixed-7x14b* with a few modifications.
* Primarily targets shell use.
* Is Named after the Bacchic mythological character, whose sister, Agave, happens to share a name with [a font I started designing earlier][agave]. Besides the name, there is no relation between the two fonts. I like superficial coherence, that's all.

## preview

**xterm**, sampling `uname` and `lua`:

![xterm](https://raw.githubusercontent.com/agarick/autonoe/master/preview-xterm.png)

**glyph distinction**, in ASCII:

![ascii](https://raw.githubusercontent.com/agarick/autonoe/master/preview-ascii.png)

## thanks

... to [FontForge][ff] and [gbdfed][gbdfed] for making this project possible.

## contact

Please email your questions and comments to *type agaric* at `agaric@protonmail.com`.
