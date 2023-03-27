--- 


title: bpbank~

pdcategory: Filters

inlets:

  1st:
  - type: signal
    description: signal to be filtered via a bank of bandpass filters

outlets:

  1st:
  - type: signal
    description: the signal filtered by the bank of filters

arguments:
  - type: float
    description: number of bandpass filters
  - type: float
    description: ramp time in ms

methods:
  - type: freq <list>
    description: list of frequencies for all filters in the bank
  - type: q <list>
    description: list of resonance (Q) for all filters in the bank
  - type: amp <list>
    description: list of amplitudes for all filters in the bank
  - type: ramp <list>
    description: list of ramp time for all filters in the bank
  - type: rampal <float>
    description: ramp time for all filters in the bank

flags:
  - type: -freq <list>
    description: sets list of frequencies for all filters
  - type: -amp <list>
    description: sets list of amplitudes for all filters
  - type: -q <list>
    description: sets list of resonance (Q) for all filters
  - type: -ramp <list>
    description: sets list of ramp time for all filters
  - type: -rampall <float>
    description: sets ramp time for all filters

draft: false
---