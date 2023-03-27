--- 


title: comb.rev~

pdcategory: Effects

inlets:

  1st:
  - type: signal
    description: signal input to the filter
  2nd:
  - type: float/signal
    description: D delay time in ms
  3rd:
  - type: float/signal
    description: a input gain coefficient
  4th:
  - type: float/signal
    description: b feedforward gain coefficient
  5th:
  - type: float/signal
    description: c feedback gain coefficient

outlets:

  1st:
  - type: signal
    description: output from comb filter

arguments:
  - type: float
    description: maximum and initial delay time in ms
  - type: float
    description: a input gain coefficient
  - type: float
    description: b feedforward gain coefficient
  - type: float
    description: c feedback gain coefficient

methods:
  - type: size <float>
    description: changes the maximum delay size (in ms)
  - type: clear
    description: clears the delay buffer



draft: false
---