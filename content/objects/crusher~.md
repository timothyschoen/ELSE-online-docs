--- 


title: crusher~

pdcategory: Effects

inlets:

  1st:
  - type: signal
    description: signal to be crushed (resampled and quantized)
  2nd:
  - type: float/signal
    description: bit reduction from 0-1
  3rd:
  - type: float/signal
    description: decimation (sample rate reduction) from 0-1

outlets:

  1st:
  - type: signal
    description: resampled and quantized signal

arguments:
  - type: float
    description: bit reduction
  - type: float
    description: decimation





draft: false
---