--- 


title: quantizer~

pdcategory: Signal Math

inlets:

  1st:
  - type: signal
    description: a float to be quantized
  2nd:
  - type: float/signal
    description: step value to quantize to

outlets:

  1st:
  - type: signal
    description: quantized signal

arguments:
  - type: float
    description: step value
  - type: float
    description: mode; 0 (round), 1 (int), 2 (floor), or 3 (ceil)

methods:
  - type: mode <float>
    description: sets approximation mode <0, 1, 2, or 3>



draft: false
---