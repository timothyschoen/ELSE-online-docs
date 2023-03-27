--- 


title: pan4~

pdcategory: Mixing and Routing

inlets:

  1st:
  - type: signal
    description: signal input
  2nd:
  - type: float/signal
    description: X pan value; from -1 (Left) to 1 (Right)
  3rd:
  - type: float/signal
    description: Y pan value; from -1 (Back) to 1 (Front)

outlets:

  1st:
  - type: signal
    description: Left-Back channel
  2nd:
  - type: signal
    description: Left-Front channel
  3rd:
  - type: signal
    description: Left-Back channel
  4th:
  - type: signal
    description: Right-Back channel

arguments:
  - type: float
    description: initial X pan value
  - type: float
    description: initial Y pan value





draft: false
---