# Code 39 Barcode generator

Simple PHP class for generating Code39 barcode images.  Really simple stuff: just do 

	barcode::code39('text to encode');

Optionally, add a height in pixels and/or a width multiplier:

	barcode::code39('text to encode', $height_in_px, $width_multiplier);

Currently it will always send the "Content-type: image/png" header and output the code. Future revisions may support writing to file, etc.
