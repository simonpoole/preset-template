Preset template
===============

The preset name needs to be set in build.gradle and in .tx/config (if you are translating the contents) 

Building the preset files is done with gradle and should work on both unixy operations systems and windows, the "generateAllPresetTypes" task will generate the variants in the `gen` directory.

Building requires `xmlstarlet` installed and on your path, generating the icons from SVG requires `rsvg-convert`to be installed.

Please follow us on [twitter](https://twitter.com/search?q=vespucci_editor) for updates.
