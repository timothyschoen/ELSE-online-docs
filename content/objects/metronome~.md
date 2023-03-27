--- 


title: metronome~

pdcategory: Triggers and Clocks

inlets:

  1st:
  - type: list
    description: count output from [metronome]

outlets:

  1st:
  - type: signal
    description: metronome clicks

arguments:
  - type: list
    description: low, mid, high frequencies

methods:
  - type: set <list>
    description: sets click frequencies (low, mid, high)

flags:
  - type: -mode <float>
    description: sets mode (0, 1, 2)

draft: false
---