--- 


title: mono.rev~

pdcategory: Effects

inlets:

  1st:
  - type: signal
    description: input signal

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
    description: room size
  - type: float
    description: high frequency damping
  - type: float
    description: wet ratio

methods:
  - type: decay <float>
    description: decay time in seconds
  - type: damp <float>
    description: high frequency damping
  - type: size <float>
    description: room size
  - type: wet <float>
    description: wet ratio
  - type: clear
    description: clears delay buffers



draft: false
---