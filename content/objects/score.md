--- 


title: score

pdcategory: Triggers and Clocks

inlets:

  1st:
  - type: start
    description: starts the sequence
  - type: stop
    description: stops the sequence
  - type: float
    description: non-0 starts, 0 stops sequence

outlets:

  1st:
  - type: anything
    description: event data
  2nd:
  - type: anything
    description: score data (bar number, tempo, etc)
  3rd:
  - type: bang
    description: when sequence is over

arguments:
  - type: symbol
    description: score file to load

methods:
  - type: pause
    description: pauses playing
  - type: continue
    description: continues playing
  - type: show
    description: opens edit window
  - type: hide
    description: closes edit window
  - type: open <symbol>
    description: import score from a file, no symbol opens dialog window
  - type: save <symbol>
    description: write score to file, no symbol opens dialog window



draft: false
---