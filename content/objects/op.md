--- 


title: op

pdcategory: Data Math

inlets:

  1st:
  - type: float/list
    description: input to operator
  2nd:
  - type: float
    description: secondary operator value (ignored for bitnot)

outlets:

  1st:
  - type: float/list
    description: operator result

arguments:
  - type: symbol
    description: operator; see [pd set] for all options
  - type: float
    description: inlet value  ignored for bitnot

methods:
  - type: <symbol>
    description: operator see [pd set] for all options



draft: false
---