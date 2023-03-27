--- 


title: openfile

pdcategory: Networking

inlets:

  1st:
  - type: bang
    description: open set file



arguments:
  - type: symbol
    description: folder/file/weblink address

methods:
  - type: open <symbol>
    description: opens folder/file/weblink specified by the symbol, if no symbol is given, the current folder is opened

flags:
  - type: -h <anything>
    description: sets to hyperlink (GUI) mode, 1st element is file to open and name to display, further arguments overwrite display.

draft: false
---