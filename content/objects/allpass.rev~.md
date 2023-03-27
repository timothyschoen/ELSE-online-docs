--- 


title: allpass.rev~

pdcategory: Filters

inlets:

  1st:
  - type: signal
    description: signal to be filtered
  2nd:
  - type: float/signal
    description: delay time in ms
  3rd:
  - type: float/signal
    description: decay time in ms

outlets:

  1st:
  - type: signal
    description: the filtered signal

arguments:
  - type: float
    description: maximum and initial delay time in ms
  - type: float
    description: decay time in ms
  - type: float
    description: non-0 sets to gain mode

methods:
  - type: size <float>
    description: changes the max delay size (in ms)
  - type: clear
    description: clears the delay buffer
  - type: gain <float>
    description: non-0 sets to gain mode



draft: false
---