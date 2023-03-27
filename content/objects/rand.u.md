--- 


title: rand.u

pdcategory: Random and Noise

inlets:

  1st:
  - type: bang
    description: generates a random output
  2nd:
  - type: float
    description: clears memory and sets a new size

outlets:

  1st:
  - type: float
    description: unrepeated random float
  2nd:
  - type: bang
    description: bang when sequence is finished

arguments:
  - type: float
    description: size

methods:
  - type: clear
    description: clears memory
  - type: seed <float>
    description: a float sets seed, no float sets a unique internal
  - type: size <float>
    description: clears the memory and sets a new 'n' size

flags:
  - type: -seed <float>
    description: sets seed

draft: false
---