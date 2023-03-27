--- 


title: out8~

pdcategory: Audio I/O

inlets:

  1st:
  - type: signal
    description: incoming signal (routed to [dac~ 1])
  2nd:
  - type: signal
    description: incoming signal (routed to [dac~ 2])
  3rd:
  - type: signal
    description: incoming signal (routed to [dac~ 3])
  4th:
  - type: signal
    description: incoming signal (routed to [dac~ 4])
  5th:
  - type: signal
    description: incoming signal (routed to [dac~ 5])
  6th:
  - type: signal
    description: incoming signal (routed to [dac~ 6])
  7th:
  - type: signal
    description: incoming signal (routed to [dac~ 7])
  8th:
  - type: signal
    description: incoming signal (routed to [dac~ 8])



arguments:
  - type: float
    description: max gain (needs to be > 0)
  - type: float
    description: scaling mode; 0 (quartic), 1 (dB), or 2 (linear)

methods:
  - type: set <float>
    description: sets slider (range is clipped to 0-1)
  - type: <on/off>
    description: turns DSP Engine (Compute Audio) On or Off
  - type: mode <float>
    description: scaling mode; 0 (quartic, default), 1 (dB) or 2 (linear)
  - type: mute
    description: mute/unmute button
  - type: gain <float>
    description: sets max gain (values <= 0 are ignored)
  - type: ramp <float>
    description: sets ramp time in ms for slider values (default 20)



draft: false
---