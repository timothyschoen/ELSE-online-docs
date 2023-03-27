--- 


title: morph

pdcategory: Data Management

inlets:

  1st:
  - type: list
    description: list with one or more elements to morph to
  2nd:
  - type: float
    description: morph time in ms
  3rd:
  - type: float
    description: grain time in ms

outlets:

  1st:
  - type: list
    description: morphed list

arguments:
  - type: float
    description: morph time in ms
  - type: float
    description: grain time in ms
  - type: list
    description: start list values

methods:
  - type: set <list>
    description: set start list values

flags:
  - type: -exp <float>
    description: sets exponential factor

draft: false
---