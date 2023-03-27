--- 


title: comb.filt~

pdcategory: Filters

inlets:

  1st:
  - type: signal
    description: signal input to the filter
  2nd:
  - type: float/signal
    description: frequency in Hz
  3rd:
  - type: float/signal
    description: decay coefficient

outlets:

  1st:
  - type: signal
    description: output from comb filter

arguments:
  - type: float
    description: maximum and initial delay time in ms
  - type: float
    description: decay coefficient
  - type: float
    description: decay mode <0> or gain mode <non-0>

methods:
  - type: clear
    description: clears the delay buffer
  - type: gain <float>
    description: non-0 sets to gain mode instead of 't60'

flags:
  - type: -gain
    description: sets feedback mode to gain

draft: false
---