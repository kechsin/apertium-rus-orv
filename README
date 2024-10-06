Russian and Olrat: `apertium-rus-olr`
===============================================================================

This is an Apertium language pair for translating between Russian and
Olrat. What you can use this language package for:

* Translating between Russian and Olrat
* Morphological analysis of Russian and Olrat
* Part-of-speech tagging of Russian and Olrat

For information on the latter two points, see subheading "For more
information" below.

Requirements
-------------------------------------------------------------------------------

You will need the following software installed:

* autoconf
* automake
* pkg-config
* lttoolbox (>= 3.5.1)
* apertium (>= 3.6.1)
* vislcg3 (>= 1.3.1)
* apertium-rus
* apertium-olr

If this does not make any sense, we recommend you look at: apertium.org.

Compiling
-------------------------------------------------------------------------------

Given the requirements being installed, you should be able to just run:

```console
$ autoreconf -fvi
$ ./configure
$ make
# make install
```

You can use `./autogen.sh` instead of `autoreconf` and `./configure` in case you're compiling
from source. If you installed any prerequisite language packages using a
`--prefix` with `./configure`, make sure to use the same `--prefix` when running
`./configure` here.

If any of this doesn't make sense or doesn't work, see https://wiki.apertium.org/wiki/Install_language_data_by_compiling

Testing
-------------------------------------------------------------------------------

If you are in the source directory after running make, the following
commands should work:

```console
$ echo "TODO test sentence 1" | apertium -d . rus-olr
TODO test translated sentence 1

$ echo "TODO test sentence 2" | apertium -d . olr-rus
TODO test translated sentence 2
```

After installing somewhere in `$PATH`, you should be able to do e.g.

```console
$ echo "TODO test sentence 1" | apertium rus-olr
TODO test translated sentence 1
```

Files and data
-------------------------------------------------------------------------------

* [`apertium-rus-olr.rus-olr.dix`](apertium-rus-olr.rus-olr.dix) - Bilingual dictionary
* [`apertium-rus-olr.rus-olr.t1x`](apertium-rus-olr.rus-olr.t1x) - Chunking rules for translating into Olrat
* [`apertium-rus-olr.olr-rus.t1x`](apertium-rus-olr.olr-rus.t1x) - Chunking rules for translating into Russian
* [`apertium-rus-olr.rus-olr.t2x`](apertium-rus-olr.rus-olr.t2x) - Interchunk rules for translating into Olrat
* [`apertium-rus-olr.olr-rus.t2x`](apertium-rus-olr.olr-rus.t2x) - Interchunk rules for translating into Russian
* [`apertium-rus-olr.rus-olr.t3x`](apertium-rus-olr.rus-olr.t3x) - Postchunk rules for translating into Olrat
* [`apertium-rus-olr.olr-rus.t3x`](apertium-rus-olr.olr-rus.t3x) - Postchunk rules for translating into Russian
* [`apertium-rus-olr.rus-olr.lrx`](apertium-rus-olr.rus-olr.lrx) - Lexical selection rules for translating into Olrat
* [`apertium-rus-olr.olr-rus.lrx`](apertium-rus-olr.olr-rus.lrx) - Lexical selection rules for translating into Russian
* [`modes.xml`](modes.xml) - Translation modes

For more information
-------------------------------------------------------------------------------

* https://wiki.apertium.org/wiki/Installation
* https://wiki.apertium.org/wiki/apertium-rus-olr
* https://wiki.apertium.org/wiki/Using_an_lttoolbox_dictionary

Help and support
-------------------------------------------------------------------------------

If you need help using this language pair or data, you can contact:

* Mailing list: apertium-stuff@lists.sourceforge.net
* IRC: `#apertium` on irc.oftc.net (irc://irc.oftc.net/#apertium)

See also the file [`AUTHORS`](AUTHORS), included in this distribution.
