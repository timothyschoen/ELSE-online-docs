--- 


title: loadbanger

pdcategory: Data Management

inlets:

  1st:
  - type: anything
    description: any message triggers bangs

outlets:

  1st:
  - type: bang
    description: bang messages at loading or when activated

arguments:
  - type: float
    description: number of outputs



flags:
  - type: -init
    description: sets loadbang to "init mode

draft: false
---