--- 


title: out1~

pdcategory: Audio I/O

inlets:

  1st:
  - type: signal
    description: incoming signal routed to a mono output output; [dac~ 1]
  - type: float
    description: sets slider (range is clipped to 0-1)



arguments:
  - type: float
    description: max gain (needs to be > 0)
  - type: float
    description: scaling mode; 0 (quartic), 1 (dB), or 2 (linear)

methods:
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

flags:
  - type: -ch <float>
    description: sets output channel (default 1)

draft: false
---