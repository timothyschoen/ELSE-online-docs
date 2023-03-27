--- 


title: plate.rev~

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
    description: pre delay in ms (0-1000)
  - type: float
    description: filter cutoff (0-1)
  - type: float
    description: high frequency damping (0-1)
  - type: float
    description: room size (0-1)
  - type: float
    description: wet ratio (0-1)

methods:
  - type: pre <float>
    description: pre delay in ms (0-1000)
  - type: cutoff <float>
    description: filter cutoff (0-1)
  - type: damp <float>
    description: high frequency damping (0-1)
  - type: size <float>
    description: room size feedback (0-1)
  - type: wet <float>
    description: wet ratio (0-1)
  - type: clear
    description: clears delay buffers



draft: false
---