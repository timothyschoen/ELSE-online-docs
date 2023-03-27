--- 


title: tempo~

pdcategory: Triggers and Clocks

inlets:

  1st:
  - type: float/signal
    description: gate (on/off)
  - type: bang
    description: sync the metronome
  2nd:
  - type: float/signal
    description: tempo in ms or bpm
  3rd:
  - type: float/signal
    description: swing deviation parameter (in %)
  4th:
  - type: float
    description: an impulse syncs the metronome

outlets:

  1st:
  - type: signal
    description: impulses at metronome beat

arguments:
  - type: float
    description: bpm/Hz/ms
  - type: float
    description: swing deviation in %

methods:
  - type: mul <float>
    description: sets multiplier
  - type: ms <f, f>
    description: sets time to ms, optional floats set tempo and swing
  - type: hz <f, f>
    description: sets time to Hz, optional floats set tempo and swing
  - type: bpm <f, f>
    description: sets time to bpm, optional floats set tempo and swing
  - type: seed <float>
    description: a float sets seed, no float sets a unique internal

flags:
  - type: -on
    description: initially turn it on
  - type: -ms
    description: sets time measure to ms
  - type: -hz
    description: sets time measure to Hz
  - type: -mul <float>
    description: sets multiplier
  - type: -seed <float>
    description: sets seed

draft: false
---