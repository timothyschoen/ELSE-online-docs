--- 


title: autofade2~

pdcategory: Mixing and Routing

inlets:

  1st:
  - type: float/signal
    description: gate; "fade in" if != 0, "fade out" otherwise
  - type: anything
    description: fade types <quartic, sin, sqrt, hann, lin, hannsin, linsin>
  - type: signal
    description: input signal to be faded in/out
  2nd:
  - type: signal
    description: input signal to be faded in/out

outlets:

  1st:
  - type: signal
    description: autofaded signal
  2nd:
  - type: float
    description: a 1 or 0 is sent when the fade in/out is finished

arguments:
  - type: symbol
    description: (optional) fade types <quartic, sin, sqrt, lin, hann, lin, hannsin, linsin>
  - type: float
    description: fade in time in ms
  - type: float
    description: fade out time in ms
  - type: float
    description: number of channels

methods:
  - type: fadein <float>
    description: fade in time in ms
  - type: fadeout <float>
    description: fade out time in ms



draft: false
---