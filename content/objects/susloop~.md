--- 


title: susloop~

pdcategory: Buffers

inlets:

  1st:
  - type: float/signal
    description: 0 to non-0; starts and loops. Non-0 to 0; loop is off
  - type: bang
    description: trigger; starts from 0 and loops
  2nd:
  - type: float/signal
    description: sets increment value (rate/speed)

outlets:

  1st:
  - type: signal
    description: the control signal for the sampler
  2nd:
  - type: float
    description: status (on; 1 / off; 0)

arguments:
  - type: float
    description: increment value
  - type: float
    description: loop start
  - type: float
    description: loop end
  - type: float
    description: sample size

methods:
  - type: release
    description: loop is off
  - type: stop
    description: stops and goes back to 0, expects a trigger to restart
  - type: pause
    description: pauses/stops incrementing
  - type: continue
    description: continues after being paused
  - type: loop <f,f>
    description: sets sustain loop range in samples <start, end>
  - type: size <float>
    description: sets sample size



draft: false
---