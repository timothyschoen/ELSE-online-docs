--- 


title: count

pdcategory: Data Math

inlets:

  1st:
  - type: bang
    description: counts
  - type: float
    description: sets new count value and outputs it
  2nd:
  - type: list
    description: updates arguments

outlets:

  1st:
  - type: float
    description: count value
  2nd:
  - type: bang
    description: bang when reaching count limits

arguments:
  - type: list
    description: 1 float sets max / 2 floats set min & max

methods:
  - type: set <float>
    description: sets new count value
  - type: reset <float>
    description: without a float, resets to the reset point, but a float sets a new reset point as well
  - type: max <float>
    description: sets maximum value
  - type: min <float>
    description: sets minimum value
  - type: up
    description: sets count direction upwards
  - type: down
    description: sets count direction downwards
  - type: alt <float>
    description: non-0 sets to alternating mode (between up/down)

flags:
  - type: -alt
    description: sets to alternating mode
  - type: reset <float>
    description: sets start & reset value

draft: false
---