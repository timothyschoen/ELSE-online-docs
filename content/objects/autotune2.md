--- 


title: autotune2

pdcategory: Tuning

inlets:

  1st:
  - type: float
    description: pitch value in cents to be retuned
  2nd:
  - type: list
    description: scale in cents

outlets:

  1st:
  - type: float
    description: retuned pitch in cents

arguments:
  - type: list
    description: scale in cents

methods:
  - type: bypass <float>
    description: non-0 sets to bypass mode



draft: false
---