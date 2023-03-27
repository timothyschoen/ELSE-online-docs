--- 


title: vocoder~

pdcategory: Effects

inlets:

  1st:
  - type: signal
    description: synth source input
  - type: list
    description: list of frequencies (in MIDI) for each channel
  2nd:
  - type: signal
    description: control source input
  3rd:
  - type: float
    description: filter Q for all channels

outlets:

  1st:
  - type: signal
    description: vocoder output

arguments:
  - type: float
    description: number of channels (obligatory)
  - type: float
    description: filter Q for all channels
  - type: list
    description: List of frequency (in MIDI) for each channel





draft: false
---