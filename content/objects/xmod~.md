--- 


title: xmod~

pdcategory: Signal Generators

inlets:

  1st:
  - type: float/signal
    description: frequency of oscillator 1
  2nd:
  - type: signal
    description: modulation index 1
  3rd:
  - type: signal
    description: frequency of oscillator 2
  4th:
  - type: signal
    description: modulation index 2

outlets:

  1st:
  - type: signal
    description: output of oscillator 1
  2nd:
  - type: signal
    description: output of oscillator 2

arguments:
  - type: float
    description: frequency of oscillator 1 in Hz
  - type: float
    description: modulation index 1
  - type: float
    description: frequency of oscillator 2 in Hz
  - type: float
    description: modulation index 2

methods:
  - type: fm
    description: sets to phase modulation
  - type: pm
    description: sets to frequency modulation

flags:
  - type: -pm
    description: sets to phase modulation (

draft: false
---