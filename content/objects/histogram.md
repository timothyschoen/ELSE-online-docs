--- 


title: histogram

pdcategory: Data Math

inlets:

  1st:
  - type: float
    description: positive integer to record into histogram
  - type: list
    description: note on pitch to record into histogram

outlets:

  1st:
  - type: list
    description: occurrences and index after input
  2nd:
  - type: list
    description: table values at 'export' message
  3rd:
  - type: float
    description: number of occurrences at 'query' message

arguments:
  - type: symbol
    description: set table name

methods:
  - type: clear
    description: clears histogram table
  - type: query <float>
    description: query number of occurrences of an index
  - type: export
    description: export histogram table as a list
  - type: import <list>
    description: import histogram data as a list
  - type: embed <float>
    description: non-0 embeds histogram data with the patch
  - type: size <float>
    description: clears and resizes table
  - type: name <symbol>
    description: sets table name

flags:
  - type: -size <float>
    description: sets table size (default 128)
  - type: -embed
    description: embeds histogram data with the patch (default don't)

draft: false
---