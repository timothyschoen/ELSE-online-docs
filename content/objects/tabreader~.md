--- 


title: tabreader~

pdcategory: Arrays and Tables

inlets:

  1st:
  - type: float/signal
    description: sets index/phase

outlets:

  1st:
  - type: signal
    description: table values

arguments:
  - type: symbol
    description: array name (optional)

methods:
  - type: set <symbol>
    description: sets an entire array to be used as a waveform
  - type: loop <float>
    description: non-0 sets loop mode
  - type: none
    description: sets to no interpolation
  - type: lin
    description: sets to linear interpolation
  - type: cos
    description: sets to cosine interpolation
  - type: cubic
    description: sets to cubic interpolation
  - type: lagrange
    description: sets to Lagrange interpolation
  - type: hermite <f, f>
    description: sets to Hermite interpolation

flags:
  - type: -lin
    description: sets interpolation type
  - type: -cos
    description: sets interpolation type
  - type: -cubic
    description: sets interpolation type
  - type: -lagrange
    description: sets interpolation type
  - type: -hermite <f, f>
    description: sets interpolation type
  - type: -none
    description: sets interpolation type
  - type: -ch <float>
    description: set initial loaded channel (default 1)
  - type: -loop
    description: sets to loop mode

draft: false
---