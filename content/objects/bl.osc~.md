--- 


title: bl.osc~

pdcategory: Signal Generators

inlets:

  1st:
  - type: float/signal
    description: frequency in Hz
  - type: anything
    description: waveform  saw, saw2, tri, square, imp
  2nd:
  - type: float/signal
    description: phase sync (resets internal phase)
  3rd:
  - type: float/signal
    description: phase offset (modulation input)

outlets:

  1st:
  - type: signal
    description: bandlimited oscillator signal

arguments:
  - type: symbol
    description: (optional) waveform  saw, saw2, tri, square, imp
  - type: float
    description: number of partials
  - type: float
    description: frequency in Hz
  - type: float
    description: phase offset

methods:
  - type: n <float>
    description: number of partials
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