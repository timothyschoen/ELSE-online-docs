--- 


title: loop

pdcategory: Triggers and Clocks

inlets:

  1st:
  - type: float
    description: sets number of iterations and starts the loop
  - type: list
    description: sets range start/end and step (optionally) and run loop
  - type: bang
    description: starts the loop
  2nd:
  - type: float
    description: sets number of iterations

outlets:

  1st:
  - type: float/bang
    description: counter output or bangs in bang mode

arguments:
  - type: float
    description: <f> — number of iterations, <f f f> — start, end, step
  - type: float
    description: sets the end value (optional)
  - type: float
    description: sets a counter step value

methods:
  - type: offset <float>
    description: sets the starting value of the counter (for float)
  - type: set <list>
    description: a float sets number of iterations, a list sets start/end and step (optionally)
  - type: step <float>
    description: sets the increment value of the counter
  - type: range <list>
    description: sets start/end values
  - type: pause
    description: stops the loop
  - type: continue
    description: continues the loop after being paused

flags:
  - type: -offset <float>
    description: sets offset value (default 0)
  - type: -step <float>
    description: sets counter step value (default 1)
  - type: -b <float>
    description: sets to bang mode

draft: false
---