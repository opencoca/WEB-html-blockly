# Blockly-HTML
Blockly blocks and generators for HTML generation and a demo with live preview.

The demo can be tested here: https://raw.githack.com/opencoca/html-blockly/master/index.html

<img src="example.png" width="500" alt="Screenshot" />

## Try the demo

The files `blockly_compressed.js`, `blocks_compressed.js`, `javascript_compressed.js` and `msg/js/en.js`
of the Blockly repository need to be present in the directory `blockly`.

## TODO Expose the newer and more flexible Snap-HTML blocks

You can simply checkout the repository https://github.com/google/blockly or unzip https://github.com/google/blockly/archive/master.zip into the directory `blockly`.
Or you can pick the files above manually to create an environment you can distribute without moving the whole Blockly source code around.

The demo saves the workspace in the local browser storage. 
Additionally, it supports importing and exporting blocks (Blockly XML) and exporting the HTML document.

A German localisation of the demo can be enabled by loading `de.js` instead of `en.js` in the header of the HTML file. (This also needs `msg/js/de.js` from Blockly.)

## Library files

The file `library_html.xml`  is the block libraries that can be used to modify the blocks using the Blockly developer tools: https://blockly-demo.appspot.com/static/demos/blockfactory/index.html

## TODO
 * Support more HTML tags and attributes
 * Enforce HTML tag-nesting rules via types
 * Many more …

## Further ideas
 * Add script-tag and allow for standard Blockly blocks in there

