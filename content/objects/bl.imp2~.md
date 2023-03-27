--- 


title: bl.imp2~

pdcategory: Signal Generators

inlets:

  1st:
  - type: float/signal
    description: frequency in Hz

outlets:

  1st:
  - type: signal
    description: two sided impulse signal

arguments:
  - type: float
    description: frequency in Hz

methods:
  - type: midi <float>
    description: non-0 sets to frequency input in MIDI pitch

flags:
  - type: -midi
    description: sets frequency input in MIDI pitch (default Hz)

draft: false
---