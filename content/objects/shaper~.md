--- 


title: shaper~

pdcategory: Effects

inlets:

  1st:
  - type: signal
    description: signal to be used as index

outlets:

  1st:
  - type: signal
    description: output of transfer function (waveshaping)

arguments:
  - type: anything
    description: array/table name/list of floats

methods:
  - type: set <symbol>
    description: array/table name to be used for lookup
  - type: list
    description: harmonic weights for internal transfer function
  - type: dc <f>
    description: DC offset for internal transfer function
  - type: norm <f>
    description: normalization for internal function on <1> or off <0>
  - type: filter <f>
    description:  normalization for internal function on <1> or off <0>

flags:
  - type: -dc
    description: DC offset for internal transfer function (default 0)
  - type: -norm <f>
    description: normalization on <1> (default) or off <0>
  - type: -fill <f>
    description: DC filter on <1> (default) or off <0>

draft: false
---