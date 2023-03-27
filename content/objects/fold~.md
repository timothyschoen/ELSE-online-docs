--- 


title: fold~

pdcategory: Signal Math

inlets:

  1st:
  - type: signal
    description: input values to be folded
  2nd:
  - type: float/signal
    description: lowest fold value
  3rd:
  - type: float/signal
    description: highest fold value

outlets:

  1st:
  - type: signal
    description: folded values

arguments:
  - type: list
    description: 2 floats set min and max, 1 float sets max value (min to 0)





draft: false
---