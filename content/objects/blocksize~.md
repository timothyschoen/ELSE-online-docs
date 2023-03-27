--- 


title: blocksize~

pdcategory: Audio I/O

inlets:

  1st:
  - type: bang
    description: get block size period or frequency

outlets:

  1st:
  - type: float
    description: block size period or frequency



methods:
  - type: samps
    description: set and get the block size period in samples
  - type: ms
    description: set and get the sample rate period in ms
  - type: hz
    description: set and get the block size frequency in Hz

flags:
  - type: -hz
    description: sets to frequency in Hz
  - type: -ms
    description: sets to period in ms

draft: false
---