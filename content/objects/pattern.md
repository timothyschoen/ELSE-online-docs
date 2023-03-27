--- 


title: pattern

pdcategory: Triggers and Clocks

inlets:

  1st:
  - type: float
    description: non-0 starts, zero stops the sequencer
  - type: bang
    description: (re)start sequencer
  - type: list
    description: sets new sequence and (re)starts sequencer
  2nd:
  - type: list
    description: sets new sequence

outlets:

  1st:
  - type: float/bang
    description: bang or index float at every new note
  2nd:
  - type: anything
    description: several sequence information

arguments:
  - type: list
    description: sets sequence

methods:
  - type: tempo <float>
    description: sets tempo in bpm
  - type: start
    description: starts the sequencer
  - type: stop
    description: stops the sequencer
  - type: clear
    description: clears sequence

flags:
  - type: -tempo <float>
    description: sets new tempo value (default 120)
  - type: -i
    description: sets to output index (default bang)

draft: false
---