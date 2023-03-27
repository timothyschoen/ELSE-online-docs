--- 


title: voices

pdcategory: Data Management

inlets:

  1st:
  - type: list
    description: MIDI note messages (note and velocity pair)
  - type: float
    description: note pitch values
  2nd:
  - type: float
    description: note velocity values
  3rd:
  - type: float
    description: release time in ms

outlets:

  1st:
  - type: list
    description: note messages

arguments:
  - type: float
    description: sets number of voices
  - type: float
    description: non-0 sets voice stealing

methods:
  - type: rel <float>
    description: sets release time in ms
  - type: offset <float>
    description: sets index offset (in the context of "list" mode)
  - type: retrig <float>
    description: non-0 sets to retrigger mode
  - type: clear
    description: clears memory without output
  - type: flush
    description: clears memory and output hanging notes
  - type: voices <float>
    description: sets number of voices (in list mode only)

flags:
  - type: -rel <f>
    description: sets release time in ms (
  - type: -retrig
    description: sets to retrigger mode <0, 1 or 2>  (
  - type: -list <float>
    description: sets to list mode

draft: false
---