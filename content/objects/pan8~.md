--- 


title: pan8~

pdcategory: Mixing and Routing

inlets:

  1st:
  - type: signal
    description: signal input
  2nd:
  - type: float/signal
    description: X horizontal value; from -1 (Left) to 1 (Right)
  3rd:
  - type: float/signal
    description: Y vertical value; from -1 (Back) to 1 (Front)
  4th:
  - type: float
    description: spread parameter (from -1 to 1)

outlets:

  1st:
  - type: signal
    description: channel output 1
  2nd:
  - type: signal
    description: channel output 2
  3rd:
  - type: signal
    description: channel output 3
  4th:
  - type: signal
    description: channel output 4
  5th:
  - type: signal
    description: channel output 5
  6th:
  - type: signal
    description: channel output 6
  7th:
  - type: signal
    description: channel output 7
  8th:
  - type: signal
    description: channel output 8





flags:
  - type: -spread
    description: sets spread parameter (default 0)
  - type: -mode
    description: sets mode <0> or <1> (default 0)

draft: false
---