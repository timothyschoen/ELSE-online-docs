--- 


title: free.rev~

pdcategory: Effects

inlets:

  1st:
  - type: signal
    description: left channel input signal
  2nd:
  - type: signal
    description: right channel input signal

outlets:

  1st:
  - type: signal
    description: left channel output
  2nd:
  - type: signal
    description: right channel output

arguments:
  - type: float
    description: decay or 'liveness' (0-1)
  - type: float
    description: high frequency damping (0-1)
  - type: float
    description: stereo width (0-1)
  - type: float
    description: wet ratio (0-1)

methods:
  - type: decay <float>
    description: decay or 'liveness' (0-1)
  - type: damp <float>
    description: high frequency damping (0-1)
  - type: width <float>
    description: stereo width (0-1)
  - type: wet <float>
    description: wet ratio (0-1)
  - type: clear
    description: clears delay lines



draft: false
---