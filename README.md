# sneakpeek

Hides header when scrolling down. Shows header when scrolling up. No external
dependencies. Similar to
[Headroom.js](https://github.com/WickyNilliams/headroom.js).

Weighs less than 1kB gzipped.

It shows/hides the header by toggling a `sneakpeek--hidden` class. Style it however
you want.

## Install

Install from npm:

    npm install sneakpeek

## Usage

With browserify:

    sneakpeek = require('sneakpeek')
    sneakpeek(document.getElementById('header'))

Regular script tags:

    <script src="index.js"></script>
    <script>
      sneakpeek(document.getElementById('header'))
    </script>

See `demo.html` for an example.