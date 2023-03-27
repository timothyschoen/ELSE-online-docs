--- 


title: lfo

pdcategory: Envelopes and LFOs

inlets:

  1st:
  - type: float
    description: frequency in Hz up to 100 (negative values accepted)
  - type: anything
    description: sets waveform (sine, tri, saw, vsaw, and square)
  2nd:
  - type: float
    description: phase reset from 0  1
  3rd:
  - type: float
    description: refresh rate in ms (minimum is 5 ms)

outlets:

  1st:
  - type: float
    description: LFO's waveform in the range from 0  127

arguments:
  - type: float
    description: sets frequency in Hz (default 0)
  - type: float
    description: sets initial phase from 0  1 (default 0)
  - type: float
    description: sets refresh rate in ms (default 5)



flags:
  - type: -sine
    description: sets waveform to sine (default)
  - type: -tri
    description: sets waveform to triangular
  - type: -saw
    description: sets waveform to sawtooth
  - type: -square <float>
    description: sets waveform to square and width (from 0 to 1)
  - type: -vsaw <float>
    description: sets waveform to variable sawtooth and width (from -1 to 1)

draft: false
---