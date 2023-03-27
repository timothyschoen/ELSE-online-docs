--- 


title: rescale~

pdcategory: Signal Math

inlets:

  1st:
  - type: signal
    description: value to perform the scaling function on
  2nd:
  - type: signal
    description: range parameters

outlets:

  1st:
  - type: signal
    description: the rescaled signal

arguments:
  - type: list
    description: <min out, max out, exp factor> or <min in, max in, min out, max out, exp factor>

methods:
  - type: exp <float>
    description: sets the exponential factor
  - type: clip <float>
    description: 1  clipping in, 0  off

flags:
  - type: -clip
    description: sets clipping on

draft: false
---