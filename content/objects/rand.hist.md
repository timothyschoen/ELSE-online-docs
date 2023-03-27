--- 


title: rand.hist

pdcategory: Random and Noise

inlets:

  1st:
  - type: bang
    description: generates a random output
  - type: list
    description: sets new histogram and clears memory

outlets:

  1st:
  - type: float
    description: random index output from histogram
  2nd:
  - type: bang
    description: bang when sequence is finished

arguments:
  - type: list
    description: sets histogram

methods:
  - type: seed <float>
    description: a float sets seed, no float sets a unique internal
  - type: set <f, f>
    description: set index and occurrence value
  - type: clear
    description: clears memory
  - type: inc <float>
    description: set index and increase occurrence by 1
  - type: dec <float>
    description: set index and decrease occurrence by 1
  - type: size <float>
    description: clears the memory and sets a new 'n' size
  - type: eq <float>
    description: sets an equal number of occurrences for all elements
  - type: unrepeat
    description: non-0 sets unrepeat mode

flags:
  - type: -seed <float>
    description: seed value
  - type: -size <float>
    description: sets histogram size
  - type: -eq <float>
    description: sets equal number of occurrences for all indexes
  - type: -u
    description: unrepeat mode

draft: false
---