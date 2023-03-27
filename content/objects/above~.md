--- 


title: above~

pdcategory: Signal Math

inlets:

  1st:
  - type: float/signal
    description: input signal
  2nd:
  - type: float/signal
    description: threshold value

outlets:

  1st:
  - type: signal
    description: when left inlet value rises above the threshold
  2nd:
  - type: signal
    description: when left inlet falls back below the threshold

arguments:
  - type: float
    description: initial threshold value





draft: false
---