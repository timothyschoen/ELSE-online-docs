--- 


title: float2bits

pdcategory: Data Math

inlets:

  1st:
  - type: float
    description: sets float value and converts to bits
  - type: bang
    description: converts to bits
  2nd:
  - type: float
    description: sets float to convert to bits

outlets:

  1st:
  - type: anything
    description: a list of bits when receiving a bang or "signal", "exponent" and "mantissa" values when receiving a 'split' message

arguments:
  - type: float
    description: sets float to convert to bits

methods:
  - type: set <float>
    description: sets float value and doesn't convert it
  - type: split
    description: sends "mantissa", "exponent" and "signal" values separately



draft: false
---