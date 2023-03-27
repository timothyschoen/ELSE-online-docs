--- 


title: markov

pdcategory: Data Management

inlets:

  1st:
  - type: bang
    description: get value from Markov chain and goes to the next

outlets:

  1st:
  - type: anything
    description: output from Markov chain

arguments:
  - type: float
    description: sets order
  - type: float
    description: non-0 sets to savestate mode

methods:
  - type: create
    description: create Markov chain from memory and go to start
  - type: clear
    description: clears memory
  - type: learn <anything>
    description: feed memory with new information
  - type: savesate <float>
    description: 
  - type: reset
    description: go to the start of the chain
  - type: random
    description: go to a random position in the chain
  - type: order <float>
    description: sets order
  - type: seed <float>
    description: a float sets seed, no float sets a unique internal

flags:
  - type: seed <float>
    description: sets seed

draft: false
---