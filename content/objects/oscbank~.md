--- 


title: oscbank~

pdcategory: Signal Generators

inlets:

  1st:
  - type: float/signal
    description: fundamental frequency in Hz

outlets:

  1st:
  - type: signal
    description: the oscillator bank output

arguments:
  - type: float
    description: number of oscillators
  - type: float
    description: fundamental frequency in Hz
  - type: float
    description: ramp time in ms

methods:
  - type: ratio <list>
    description: list of ratios for all oscillators
  - type: amp <list>
    description: list of amplitudes for all oscillators
  - type: phase <list>
    description: list of phases (0-1) for all oscillators
  - type: ramp <list>
    description: list of ramp time for all oscillators
  - type: rampall <float>
    description: sets ramp time for all oscillators

flags:
  - type: -ratio <list>
    description: sets list of ratios for all oscillators (default all 1)
  - type: -amp <list>
    description: sets list of amplitudes for all oscillators (default all 1)
  - type: -phase <list>
    description: sets list of phases for all oscillators (default all 0)
  - type: -ramp <list>
    description: sets list of ramp times for all oscillators
  - type: -freq <float>
    description: sets fundamental frequency in Hz (default 0)
  - type: -rampall <float>
    description: sets a ramp time for all oscillators (default all 10)

draft: false
---