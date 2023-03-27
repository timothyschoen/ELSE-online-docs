--- 


title: biquads~

pdcategory: Filters

inlets:

  1st:
  - type: signal
    description: the signal to be filtered
  - type: list
    description: list of biquad coefficients

outlets:

  1st:
  - type: signal
    description: the filtered signal



methods:
  - type: clear
    description: clears the filter's memory
  - type: bypass <float>
    description: <1> bypasses the input, <0> turns the filter on



draft: false
---