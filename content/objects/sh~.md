--- 


title: sh~

pdcategory: Triggers and Clocks

inlets:

  1st:
  - type: float/signal
    description: input to sample and hold
  - type: bang
    description: sample the signal
  2nd:
  - type: signal
    description: gate signal

outlets:

  1st:
  - type: signal
    description: sampled and held signal

arguments:
  - type: float
    description: initial threshold
  - type: float
    description: initially held value
  - type: float
    description: modes  0 (gate) or 1 (trigger)

methods:
  - type: set <f>
    description: set the held value
  - type: gate
    description: set the gate mode
  - type: trigger
    description: set the trigger mode

flags:
  - type: -tr
    description: sets to trigger mode

draft: false
---