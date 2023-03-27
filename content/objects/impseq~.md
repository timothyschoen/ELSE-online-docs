--- 


title: impseq~

pdcategory: Signal Generators

inlets:

  1st:
  - type: signal
    description: trigger to generate impulse from sequence
  - type: bang
    description: generates impulse from sequence at control rate
  - type: list
    description: 1 or more floats set sequence values and outputs the first

outlets:

  1st:
  - type: signal
    description: impulse value from a sequence
  2nd:
  - type: signal
    description: impulse when reaching end of sequence

arguments:
  - type: list
    description: list of floats sets the sequence

methods:
  - type: set <list>
    description: sets one or more impulse values without outputting
  - type: goto <float>
    description: goes to a position index in the sequence (from 1)



draft: false
---