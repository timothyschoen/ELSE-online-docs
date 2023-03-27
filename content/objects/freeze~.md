--- 


title: freeze~

pdcategory: Effects

inlets:

  1st:
  - type: signal
    description: input to freeze
  2nd:
  - type: float
    description: non-0 freezes (or refreezes), 0 unfreezes

outlets:

  1st:
  - type: signal
    description: freeze output



methods:
  - type: freeze
    description: (re)freezes
  - type: unfreeze
    description: unfreezes



draft: false
---