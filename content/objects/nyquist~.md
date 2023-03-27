--- 


title: nyquist~

pdcategory: Analysis

inlets:

  1st:
  - type: bang
    description: get Nyquist frequency or period

outlets:

  1st:
  - type: float
    description: Nyquist frequency or period



methods:
  - type: hz
    description: set and get the Nyquist frequency in Hz
  - type: khz
    description: set and get the Nyquist frequency in kHz
  - type: ms
    description: set and get the Nyquist period in ms
  - type: sec
    description: set and get the Nyquist period in seconds

flags:
  - type: -khz
    description: sets to frequency in kHz
  - type: -ms
    description: sets to period in ms
  - type: -sec
    description: sets to period in seconds

draft: false
---