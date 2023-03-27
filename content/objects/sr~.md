--- 


title: sr~

pdcategory: Signal Math

inlets:

  1st:
  - type: bang
    description: get sample rate frequency or period

outlets:

  1st:
  - type: float
    description: sample rate frequency or period



methods:
  - type: hz
    description: set and get the sample rate frequency in Hz
  - type: khz
    description: set and get the sample rate frequency in kHz
  - type: ms
    description: set and get the sample rate period in ms
  - type: sec
    description: set and get the sample rate period in seconds

flags:
  - type: -khz
    description: sets output to frequency in kHz
  - type: -ms
    description: sets output to period ms
  - type: -sec
    description: sets output to period in seconds

draft: false
---