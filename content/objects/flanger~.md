--- 


title: flanger~

pdcategory: Effects

inlets:

  1st:
  - type: signal
    description: flanger input
  2nd:
  - type: float
    description: rate in Hz
  3rd:
  - type: float
    description: depth (ms)
  4th:
  - type: float
    description: coefficient for feedforward/feedback lines

outlets:

  1st:
  - type: signal
    description: flanger output

arguments:
  - type: float
    description: rate in Hz
  - type: float
    description: depth in ms
  - type: float
    description: coefficient



flags:
  - type: -tri
    description: sets waveform to triangular (default sine)

draft: false
---