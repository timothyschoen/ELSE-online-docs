--- 


title: rescale

pdcategory: MIDI

inlets:

  1st:
  - type: float/list
    description: original value(s)
  - type: bang
    description: outputs the last rescaled float value
  2nd:
  - type: float
    description: range parameters

outlets:

  1st:
  - type: float/list
    description: the rescaled value(s)

arguments:
  - type: list
    description: <min out, max out, exp factor> or <min in, max in, min out, max out, exp factor>

methods:
  - type: set
    description: sets the next value to be rescaled via bang
  - type: exp <float>
    description: sets the exponential factor
  - type: clip <float>
    description: 1  clipping in, 0  off

flags:
  - type: -clip
    description: sets clipping on

draft: false
---