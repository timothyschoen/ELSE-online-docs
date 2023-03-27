--- 


title: stereo.rev~

pdcategory: Effects

inlets:

  1st:
  - type: signal
    description: left input signal
  2nd:
  - type: signal
    description: right input signal

outlets:

  1st:
  - type: signal
    description: left channel output
  2nd:
  - type: signal
    description: right channel output

arguments:
  - type: float
    description: decay in seconds
  - type: float
    description: room size (0-1)
  - type: float
    description: high frequency damping
  - type: float
    description: wet ratio

methods:
  - type: decay <float>
    description: decay time in seconds
  - type: damp <float>
    description: high frequency damping in Hz
  - type: size <float>
    description: room size (0-1)
  - type: wet <float>
    description: room size (0-1)
  - type: clear
    description: clears delay buffers



draft: false
---