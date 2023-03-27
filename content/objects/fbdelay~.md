--- 


title: fbdelay~

pdcategory: Effects

inlets:

  1st:
  - type: signal
    description: signal input to the delay line
  2nd:
  - type: float/signal
    description: delay time (im ms)
  3rd:
  - type: float/signal
    description: decay time (in ms)

outlets:

  1st:
  - type: signal
    description: the filtered/delayed signal

arguments:
  - type: float
    description: delay time
  - type: float
    description: feedback amount
  - type: float
    description: feedback mode; <0> ("t60") or <non-0> (gain mode)

methods:
  - type: size <float>
    description: changes the maximum delay size (in ms)
  - type: freeze <float>
    description: non-0 freezes, zero unfreezes
  - type: clear
    description: clears the delay buffer
  - type: gain <float>
    description: non-0 sets to gain mode

flags:
  - type: -size <float>
    description: sets delay size (default 1000 ms or first argument's value if given)
  - type: -samps
    description: sets delay time unit to "samples" (default is ms)
  - type: -gain
    description: sets feedback mode to gain

draft: false
---