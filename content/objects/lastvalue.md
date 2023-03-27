--- 


title: lastvalue

pdcategory: Analysis

inlets:

  1st:
  - type: float
    description: stores value and outputs last value
  - type: bang
    description: outputs last stored value
  2nd:
  - type: float
    description: sets last value
  - type: bang
    description: sets last value to none

outlets:

  1st:
  - type: float
    description: last input value

arguments:
  - type: float
    description: initial last value

methods:
  - type: reset <float>
    description: resets object and sets last value, no float sets to none



draft: false
---