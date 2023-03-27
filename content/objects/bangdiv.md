--- 


title: bangdiv

pdcategory: Triggers and Clocks

inlets:

  1st:
  - type: bang
    description: bang signal to be divided
  2nd:
  - type: float
    description: sets the divisor value (minimum=1)

outlets:

  1st:
  - type: bang
    description: first bang
  2nd:
  - type: bang
    description: subsequent bangs until divisor value is hit

arguments:
  - type: float
    description: divisor value
  - type: float
    description: start count value

methods:
  - type: div <float>
    description: sets the divisor value
  - type: start <float>
    description: sets the start value
  - type: reset
    description: resets the counter to the start value



draft: false
---