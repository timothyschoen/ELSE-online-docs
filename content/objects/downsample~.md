--- 


title: downsample~

pdcategory: Effects

inlets:

  1st:
  - type: signal
    description: signal to be downsampled
  - type: bang
    description: restart cycle and sync output
  2nd:
  - type: float/signal
    description: rate (in Hz) used to downsample the input signal

outlets:

  1st:
  - type: signal
    description: downsampled signal

arguments:
  - type: float
    description: rate in Hz
  - type: float
    description: interpolation 0 (off) or 1 (on)

methods:
  - type: interp <float>
    description: interpolation 0 (off, default) or 1 (on)



draft: false
---