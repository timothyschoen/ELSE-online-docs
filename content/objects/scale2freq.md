--- 


title: scale2freq

pdcategory: Tuning

inlets:

  1st:
  - type: list
    description: scale in cents to convert to a frequency list
  - type: bang
    description: generate frequency list

outlets:

  1st:
  - type: list
    description: frequency list

arguments:
  - type: list
    description: scale in cents

methods:
  - type: base <float>
    description: sets base pitch value in MIDI
  - type: range <f, f>
    description: sets min/max frequency range in Hz

flags:
  - type: -base <float>
    description: sets base pitch value in MIDI (default 60)
  - type: -range <float float>
    description: sets min/max frequency range in Hz (default 20 20000)

draft: false
---