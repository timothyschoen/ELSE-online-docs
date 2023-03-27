--- 


title: sequencer

pdcategory: Triggers and Clocks

inlets:

  1st:
  - type: bang
    description: gets element(s) from sequence
  - type: float
    description: sets index (from 1) and outputs it
  2nd:
  - type: list
    description: sets a new sequence
  - type: bang
    description: sets an empty sequence

outlets:

  1st:
  - type: float
    description: element(s) from a sequence
  2nd:
  - type: bang
    description: when there is a rest
  3rd:
  - type: float
    description: bar number
  4th:
  - type: bang
    description: when reaching end of sequence

arguments:
  - type: list
    description: list of elements sets the sequence

methods:
  - type: goto <f>
    description: goes to a position index in the sequence (from 1)
  - type: set <list>
    description: set a new sequence
  - type: clear
    description: clears sequence



draft: false
---