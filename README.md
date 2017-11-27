# cl-unescape
Tiny lib to unescape html entities – mostly useful due to comprehensive char list.

## Probably, better solution would be [BnMcGn/html-entities](https://github.com/BnMcGn/html-entities/)

Based on https://github.com/acieroid/clpages/blob/666ab6097d3abdbf607a1d1c5ea4bad13e712bd0/unescape.lisp

Diffs from original:
+ skipping junk like "&#nnnn;"
+ extended list of chars
