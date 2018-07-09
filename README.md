# Lorem Ipsum Generator for Sketch

A plugin for [Sketch](http://sketchapp.com) to insert Lorem Ipsum into any selected text fields. Originally by [@richgong](https://github.com/richgong/sketch-lorem-ipsum-2017), I forked this to add more Lorem.

Currently features unique 10 paragraphs of Lorem Ipsum.

## Installation

1. Download or clone this repository
2. Double click the `.sketchplugin` file to open Sketch and install the plugin

## How to use

1. Select text fields
2. Use the keyboard shortcut: `Shift + Ctrl + L` 

You can also use the plugin from the menu (Plugins > Lorem Ipsum Generator > Fill out text fields)

## Todo

* Limit the amount of Lorem inserted by the text field size. Plugin currently shoves an entire paragraph into each text field, no matter the length, requiring users to manually delete text each time. Solution: Calculate length of text container + size of glyphs ([see script from Sketch-Highlighter](https://github.com/matt-curtis/Sketch-Highlighter/blob/master/Sketch-Highlighter.sketchplugin/Contents/Sketch/script.js) - search for `textLayer.frame().size().width,` and `layoutManager.numberOfGlyphs();`)
* An actual Lipsum generator algorithm (*without connecting to lipsum.com*)