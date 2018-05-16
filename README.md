# prosemirror-webpack-project

A bare minimal webpack project to bundle a prosemirror to get started

prosemirror-example-setup npm module is not a turn-key example for prosemirror because it is not bundled.

This project (as of May 2018) creates a simple webpack bundle that can be included in an html file in a
single script tag. 

# Install:

`npm install`

# Building:

Run:

  `./node_modules/bin/webpack`

This will create a file `dist/bundle.js` 

Include it as a script tag in your html file.

# Sources:

The example minimal editor in http://prosemirror.net/examples/basic/ is placed in src/editor.js


# Notes:

Note, the editor will appear on your page, but in an awkward fashion. You need to include CSS files.