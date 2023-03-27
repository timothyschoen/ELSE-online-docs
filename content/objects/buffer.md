--- 


title: buffer

pdcategory: Arrays and Tables

inlets:

  1st:
  - type: list
    description: resize, set array and output list
  - type: bang
    description: output array
  2nd:
  - type: list
    description: resize and set array

outlets:

  1st:
  - type: list
    description: array values

arguments:
  - type: symbol
    description: array name

methods:
  - type: set <list>
    description: 1st item is index, the next are values from that index
  - type: name <symbol>
    description: set array name



draft: false
---