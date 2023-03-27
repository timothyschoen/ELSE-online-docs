--- 


title: clock

pdcategory: Triggers and Clocks

inlets:

  1st:
  - type: float
    description: non-0 starts the clock, zero stops it
  - type: bang
    description: resyncs the clock
  2nd:
  - type: float
    description: BPM for main clock or multiplier for synced clock
  - type: symbol
    description: multiplier fraction for synced clocks

outlets:

  1st:
  - type: bang
    description: bang according to clock tempo

arguments:
  - type: symbol
    description: (optional) clock name
  - type: float/symbol
    description: BPM for main clock, or divider for synced clocks

methods:
  - type: beat <float>
    description: sets beat length

flags:
  - type: -s
    description: set to synced clock (default main)

draft: false
---