--- 


title: bicoeff

pdcategory: Filters

inlets:

  1st:
  - type: anything
    description: <allpass, lowpass, highpass, bandpass, resonant, bandstop, eq, lowshelf, highshelf>

outlets:

  1st:
  - type: list
    description: 5 coefficients for the vanilla [biquad~] object





flags:
  - type: -dim <f,f>
    description: width, height (
  - type: -type <fsymbol>
    description: filter type (

draft: false
---