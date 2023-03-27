--- 


title: compress~

pdcategory: Effects

inlets:

  1st:
  - type: signal
    description: input signal

outlets:

  1st:
  - type: signal
    description: compressed signal
  2nd:
  - type: float
    description: reduction in dB

arguments:
  - type: float
    description: threshold in dB
  - type: float
    description: attenuation ratio (default 1)
  - type: float
    description: attack time in ms
  - type: float
    description: release time in ms
  - type: float
    description: output gain adjustment in dB
  - type: float
    description: RMS average size in samples

methods:
  - type: thresh <float>
    description: sets threshold in dB
  - type: ratio <float>
    description: sets attenuation ratio
  - type: attack <float>
    description: sets attack time in ms
  - type: release <float>
    description: sets release time in ms
  - type: gain <float>
    description: output gain adjustment in dB
  - type: size <float>
    description: RMS average size in samples (from 1 to 512)



draft: false
---