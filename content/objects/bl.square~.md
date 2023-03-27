--- 


title: bl.square~

pdcategory: Signal Generators

inlets:

  1st:
  - type: float/signal
    description: frequency in Hz
  2nd:
  - type: float/signal
    description: pulse width (from 0 to 1)
  3rd:
  - type: float/signal
    description: phase sync (resets internal phase)
  4th:
  - type: float/signal
    description: phase offset (modulation input)

outlets:

  1st:
  - type: signal
    description: square wave signal

arguments:
  - type: float
    description: frequency in Hz
  - type: float
    description: initial pulse width
  - type: float
    description: initial phase offset

methods:
  - type: midi <float>
    description: non-0 sets to frequency input in MIDI pitch
  - type: soft <float>
    description: non-0 sets to soft sync mode

flags:
  - type: -midi
    description: sets frequency input in MIDI pitch (default Hz)
  - type: -soft
    description: sets to soft sync mode (default hard)

draft: false
---