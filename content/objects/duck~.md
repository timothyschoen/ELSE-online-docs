--- 


title: duck~

pdcategory: Effects

inlets:

  1st:
  - type: signal
    description: input signal
  2nd:
  - type: signal
    description: control signal

outlets:

  1st:
  - type: signal
    description: ducked signal alone or mixed with control signal

arguments:
  - type: float
    description: threshold in dB
  - type: float
    description: attenuation ratio
  - type: float
    description: attack time in ms
  - type: float
    description: release time in ms

methods:
  - type: thresh <float>
    description: sets threshold in dB
  - type: ratio <float>
    description: sets attenuation ratio
  - type: attack <float>
    description: sets attack time in ms
  - type: release <float>
    description: sets release time in ms
  - type: mix <float>
    description: non-0 mixes with control signal

flags:
  - type: -mix
    description: mixes with control signal

draft: false
---