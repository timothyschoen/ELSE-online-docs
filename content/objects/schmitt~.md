--- 


title: schmitt~

pdcategory: Triggers and Clocks

inlets:

  1st:
  - type: float/signal
    description: values to analyze
  2nd:
  - type: float/signal
    description: low threshold level
  3rd:
  - type: float/signal
    description: high threshold level

outlets:

  1st:
  - type: signal
    description: 1/0 depending on the analysis

arguments:
  - type: float
    description: low threshold
  - type: float
    description: high threshold





draft: false
---