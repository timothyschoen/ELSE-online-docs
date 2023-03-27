--- 


title: blip~

pdcategory: Signal Generators

inlets:

  1st:
  - type: float/signal
    description: fundamental frequency in Hz
  2nd:
  - type: signal
    description: impulses reset phase
  3rd:
  - type: float/signal
    description: phase modulation input
  4th:
  - type: float/signal
    description: spectral multiplier

outlets:

  1st:
  - type: signal
    description: band limited oscillator output

arguments:
  - type: float
    description: fundamental frequency in Hz
  - type: float
    description: number of partials
  - type: float
    description: spectral multiplier
  - type: float
    description: lowest harmonic

methods:
  - type: n <float>
    description: number of partials
  - type: low <float>
    description: lowest harmonic
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