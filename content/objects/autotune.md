--- 


title: autotune

pdcategory: Tuning

inlets:

  1st:
  - type: float
    description: MIDI pitch to be retuned
  2nd:
  - type: list
    description: scale in cents

outlets:

  1st:
  - type: float
    description: retuned MIDI pitch

arguments:
  - type: list
    description: scale in cents

methods:
  - type: base <float>
    description: MIDI pitch base
  - type: bypass <float>
    description: non-0 sets to bypass mode

flags:
  - type: -base <float>
    description: base MIDI pitch (default 60)

draft: false
---