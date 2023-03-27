--- 


title: tempo

pdcategory: Triggers and Clocks

inlets:

  1st:
  - type: float
    description: toggle (on/off)
  - type: bang
    description: sync the metronome
  2nd:
  - type: float
    description: tempo in ms, Hz or bpm
  3rd:
  - type: float
    description: swing deviation parameter (in %)

outlets:

  1st:
  - type: bang
    description: swing deviation parameter (in %)

arguments:
  - type: float
    description: bpm/Hz/ms
  - type: float
    description: swing deviation in %

methods:
  - type: start
    description: turn the metronome on
  - type: mul <float>
    description: sets tempo subdivision
  - type: stop
    description: turn the metronome off
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
    description: sets tempo subdivision
  - type: -seed <float>
    description: sets seed

draft: false
---