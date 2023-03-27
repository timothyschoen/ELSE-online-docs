--- 


title: mtx.ctl

pdcategory: UI

inlets:

  1st:
  - type: list
    description: sets and outputs column, row and status

outlets:

  1st:
  - type: list
    description: column, row, status



methods:
  - type: set <list>
    description: sets column, row and status (no output)
  - type: get <list>
    description: outputs value of row/column
  - type: clear
    description: clears active cells
  - type: flush
    description: flushes active cell values
  - type: export
    description: exports contents as an array
  - type: import
    description: imports contents as an array
  - type: rows <float>
    description: sets number of rows
  - type: columns <float>
    description: sets number of columns
  - type: size <float>
    description: sets cell size in pixels
  - type: embed <float>
    description: non-0 save internal contents with the object

flags:
  - type: -n <f, f>
    description: number of columns and rows
  - type: -size <float>
    description: cell size in pixels
  - type: -embed
    description: embed flag

draft: false
---