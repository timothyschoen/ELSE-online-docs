--- 


title: balance~

pdcategory: Mixing and Routing

inlets:

  1st:
  - type: signal
    description: left signal input
  2nd:
  - type: signal
    description: right signal input
  3rd:
  - type: float/signal
    description: balance value = from -1 (L) to 1 (R)

outlets:

  1st:
  - type: signal
    description: left channel
  2nd:
  - type: signal
    description: right channel

arguments:
  - type: float
    description: initial balance value





draft: false
---