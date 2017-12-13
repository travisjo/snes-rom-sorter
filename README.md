# snes-rom-sorter
Python script for sorting SNES ROMs into folder for region/verified/etc.

I made this script to sort a set of SNES ROMs into a usable form for a Super EverDrive ROM cart.

## Instructions
1. Place your ROM files into the Unsorted folder
2. Run `./sort_roms`


### Customizing folder names and categories
If you don't like the categories the ROMs are being sorted into you can edit the source for `sort_roms` and adjust the categories and ignore list and run `sort_roms` again. ROM files will be unsorted back into the `Unsorted` directory prior to re-sorting back into your updated categories. Categories sort by running regular expressions against the file's name. If you need a primer on regular expressions you can just Google `regular expression`. There's a nice tester here at https://regexr.com.


# Disclaimer

It is illegal to download ROM files of cartridges you don't personally own. I'm not responsible for your actions.
