--- 


title: iterate

pdcategory: Data Management

inlets:

  1st:
  - type: bang
    description: outputs the last received input as sequential elements
  - type: anything
    description: split elements sequentially
  2nd:
  - type: float
    description: sets direction >= 0 is left to right, < 0 is reverse

outlets:

  1st:
  - type: float/symbol
    description: according to the input element, in sequential order

arguments:
  - type: float
    description: direction, >= 0 is left to right, < 0 is reverse



flags:
  - type: -trim
    description: trims symbol selector on the output

draft: false
---