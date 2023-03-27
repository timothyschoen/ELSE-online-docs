--- 


title: wavetable~

pdcategory: Signal Generators

inlets:

  1st:
  - type: float/signal
    description: sets frequency in Hz
  2nd:
  - type: float/signal
    description: phase sync (resets internal phase)
  3rd:
  - type: float/signal
    description: phase offset (modulation input)

outlets:

  1st:
  - type: signal
    description: a periodically repeating waveform

arguments:
  - type: symbol
    description: array name (optional)
  - type: float
    description: sets frequency in Hz
  - type: float
    description: sets phase offset

methods:
  - type: set <symbol>
    description: sets an entire array to be used as a waveform
  - type: size <float>
    description: sets size in number of points
  - type: offset <float>
    description: sets offset in table
  - type: midi <float>
    description: non-0 sets to frequency input in MIDI pitch
  - type: soft <float>
    description: non-0 sets to soft sync mode
  - type: none
    description: sets to no interpolation mode
  - type: lin
    description: sets to linear interpolation mode
  - type: cos
    description: sets to cosine interpolation mode
  - type: lagrange
    description: sets to Lagrange interpolation mode
  - type: spline
    description: sets to spline interpolation mode (default)

flags:
  - type: -none/-lin/-cos/-lagrange
    description: set interpolation mode (default spline)
  - type: -size <float>
    description: sets table size in points (default whole table)
  - type: -offset <float>
    description: sets table offset (default 0)
  - type: -midi
    description: sets frequency input in MIDI pitch (default Hz)
  - type: -soft
    description: sets to soft sync mode (default hard)

draft: false
---