--- 


title: chrono

pdcategory: Triggers and Clocks

inlets:

  1st:
  - type: bang
    description: rewinds chronometer or timer
  - type: float
    description: rewinds chronometer or non-0 starts or continues, zero stops
  - type: list
    description: sets timer length in minutes / seconds

outlets:

  1st:
  - type: symbol
    description: current time
  2nd:
  - type: bang
    description: when timer function finishes

arguments:
  - type: list
    description: sets timer length in minutes/seconds



flags:
  - type: -h
    description: also outputs hours for the chronometer
  - type: -t
    description: sets to timer function

draft: false
---