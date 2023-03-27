--- 


title: op~

pdcategory: Signal Math

inlets:

  1st:
  - type: signal
    description: input to operator
  2nd:
  - type: float
    description: secondary operator value (ignored for bitnot)

outlets:

  1st:
  - type: signal
    description: operator result

arguments:
  - type: symbol
    description: operator. >, <, >=, <=, ==, !=, &&, ||, &, |, ~, ^, >>, <<, or %
  - type: float/signal
    description: inlet value  ignored for bitnot

methods:
  - type: <symbol>
    description: operator; >, <, >=, <=, ==, !=, &&, ||, &, |, ~, ^, >> and <<



draft: false
---