--- 


title: oscbank2~

pdcategory: Signal Generators

inlets:

  1st:
  - type: freq <list>
    description: list of frequencies for all oscillators in the bank
  - type: amp <list>
    description: list of amplitudes for all oscillators in the bank
  - type: phase <list>
    description: list of phases (0-1) for all oscillators in the bank
  - type: ramp <list>
    description: list of ramp time for all oscillators in the bank
  - type: rampall <float>
    description: sets ramp time for all oscillators

outlets:

  1st:
  - type: signal
    description: the oscillator bank output

arguments:
  - type: float
    description: number of oscillators
  - type: float
    description: ramp time in ms

methods:
  - type: freq <list>
    description: list of frequencies for all oscillators in the bank
  - type: amp <list>
    description: list of amplitudes for all oscillators in the bank
  - type: phase <list>
    description: list of phases (0-1) for all oscillators in the bank
  - type: ramp <list>
    description: list of ramp time for all oscillators in the bank
  - type: rampall <float>
    description: sets ramp time for all oscillators

flags:
  - type: -freq <list>
    description: sets list of frequencies for all oscillators
  - type: -amp <list>
    description: sets list of amplitudes for all oscillators
  - type: -phase <list>
    description: sets list of phases for all oscillators
  - type: -ramp <list>
    description: sets ramp time for all oscillators
  - type: -rampall <float>
    description: sets a ramp time for all oscillators (default all 10)

draft: false
---