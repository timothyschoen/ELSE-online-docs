--- 


title: metronome

pdcategory: Triggers and Clocks

inlets:

  1st:
  - type: bang
    description: start or restart metronome
  - type: float
    description: non-0 (re)starts, zero stops
  2nd:
  - type: float
    description: set tempo value in BPM

outlets:

  1st:
  - type: bang
    description: bang at every beat
  2nd:
  - type: list
    description: bar, sub-bar, beat, sub-beat count
  3rd:
  - type: float
    description: beat phase (0-1)
  4th:
  - type: list
    description: actual beat length, actual tempo and bar duration in ms

arguments:
  - type: float
    description: tempo in BPM

methods:
  - type: start
    description: start or restart metronome
  - type: stop
    description: stop metronome
  - type: pause
    description: pause metronome
  - type: continue
    description: continue if paused
  - type: beat <symbol>
    description: set a beat length
  - type: timesig <sym, f>
    description: set time signature symbol and group value
  - type: sub <float>
    description: sets to subdivision (subtempo) mode
  - type: tempo <float>
    description: set tempo value in BPM

flags:
  - type: -name <symbol>
    description: set a clock name
  - type: -beat <symbol>
    description: set a beat length
  - type: -sub
    description: sets to subdivision (subtempo) mode

draft: false
---