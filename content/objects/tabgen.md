--- 


title: tabgen

pdcategory: Arrays and Tables

inlets:

  1st:
  - type: anything
    description: commands to generate functions (details in [pd examples])



arguments:
  - type: float
    description: (optional) sets array size at initialization
  - type: symbol
    description: set table name
  - type: anything
    description: commands to generate functions

methods:
  - type: size <float>
    description: resize table (needs to regenerate table)
  - type: set <symbol>
    description: sets table name
  - type: clear
    description: clear table

flags:
  - type: -ms
    description: set table size to ms (default points)

draft: false
---