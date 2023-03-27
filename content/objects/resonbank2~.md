--- 


title: resonbank2~

pdcategory: Filters

inlets:

  1st:
  - type: signal
    description: signal to be filtered via a bank of resonators

outlets:

  1st:
  - type: signal
    description: filtered signal

arguments:
  - type: float
    description: number of filters
  - type: float
    description: ramp time in ms

methods:
  - type: freq <list>
    description: list of frequencies for all filters
  - type: attack <list>
    description: list of attack times for all filters
  - type: decay <list>
    description: list of decay times for all filters
  - type: amp <list>
    description: list of amplitudes for all filters
  - type: ramp <list>
    description: list of ramp times for all filters
  - type: rampall <float>
    description: sets ramp time for all filters

flags:
  - type: -freq <list>
    description: list of frequencies for all filters
  - type: -attack <list>
    description: list of attack times for all filters
  - type: -decay <list>
    description: list of decay times for all filters
  - type: -amp <list>
    description: list of amplitudes for all filters
  - type: -ramp <list>
    description: list of ramp times for all filters
  - type: -rampall <float>
    description: sets ramp time for all filters

draft: false
---