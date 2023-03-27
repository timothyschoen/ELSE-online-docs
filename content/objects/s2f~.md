--- 


title: s2f~

pdcategory: Signal Math

inlets:

  1st:
  - type: signal
    description: signal value to convert to float
  - type: bang
    description: syncs the conversion rate
  2nd:
  - type: float
    description: conversion time in ms

outlets:

  1st:
  - type: float
    description: converted float

arguments:
  - type: float
    description: self-clocking interval in ms
  - type: float
    description: sample offset within the block

methods:
  - type: set <float>
    description: sets the time without syncing
  - type: float
    description: turns on (non-0) or off (0)
  - type: start
    description: turns on
  - type: stop
    description: turns off
  - type: offset <float>
    description: sets the sample offset within the block

flags:
  - type: -off
    description: turns it off (

draft: false
---