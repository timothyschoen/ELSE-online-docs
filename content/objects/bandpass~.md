--- 


title: bandpass~

pdcategory: Filters

inlets:

  1st:
  - type: signal
    description: signal to be filtered
  2nd:
  - type: signal
    description: central frequency in Hz
  3rd:
  - type: signal
    description: filter resonance (Q or bandwidth)

outlets:

  1st:
  - type: signal
    description: filtered signal

arguments:
  - type: float
    description: central frequency in Hz
  - type: float
    description: resonance, either in Q (default) or bandwidth

methods:
  - type: clear
    description: clears filter's memory if you blow it up
  - type: bypass <float>
    description: 1 (bypasses input signal) or 0 (doesn't bypass)
  - type: bw
    description: sets resonance parameter to bandwidth in octaves
  - type: q
    description: sets resonance parameter to Q (default)

flags:
  - type: -bw
    description: sets resonance parameter to bandwidth in octaves

draft: false
---