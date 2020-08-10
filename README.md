# easy-peasy-svgeezy
Example code for generating SVG sprites on the fly using svg-sprite and NPM scripts.

See blog post here for more details: https://www.mediasuite.co.nz/blog/generating-svg-sprites-the-easy-way

## Usage

First install svg-sprite and SVG for Everybody packages by running:
```
// Using NPM:
npm i

// Or Yarn...
yarn
```

Generate SVG sprite (using symbols):
```
npm run update-sprite

// Or Yarn...
yarn run update-sprite
```
(See index.html for example of how to embed SVGs using external reference, including
and intialising SVG for Everybody polyfill etc)

Generate sprite and serve preview page on localhost:8000 (note: may need to install
Python or find alternative local server if not on OSX/Linux):
```
npm run serve-example

// Or Yarn...
yarn run serve-example
```

The index.html file in the root directory can be manually edited to test different
embed methods etc. To serve sandbox HTML file on localhost:8000, run:
```
npm run serve-sandbox

// Or Yarn...
yarn run serve-example
```

