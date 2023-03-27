--- 


title: mix4~

pdcategory: UI

inlets:

  1st:
  - type: signal
    description: incoming signal for channel 1
  2nd:
  - type: signal
    description: incoming signal for channel 2
  3rd:
  - type: signal
    description: incoming signal for channel 3
  4th:
  - type: signal
    description: incoming signal for channel 4

outlets:

  1st:
  - type: signal
    description: left channel signal
  2nd:
  - type: signal
    description: right channel signal

arguments:
  - type: float
    description: scaling mode;0 (quartic), 1 (dB) or 2 (linear)

methods:
  - type: gain <float>
    description: sets gain for channel 1
  - type: gain2 <float>
    description: sets gain for channel 2
  - type: gain3 <float>
    description: sets gain for channel 3
  - type: gain4 <float>
    description: sets gain for channel 4
  - type: pan <float>
    description: sets pan for channel 1
  - type: pan2 <float>
    description: sets pan for channel 2
  - type: pan3 <float>
    description: sets pan for channel 3
  - type: pan4 <float>
    description: sets pan for channel 4
  - type: mode <float>
    description: sets scaling mode; 0 (quartic), 1 (dB) or 2 (linear)



draft: false
---