--- 


title: stack

pdcategory: Data Management

inlets:

  1st:
  - type: bang
    description: outputs and removes a message
  2nd:
  - type: anything
    description: input messages to be stacked

outlets:

  1st:
  - type: anything
    description: the stored message
  2nd:
  - type: float
    description: number of stacked messages

arguments:
  - type: symbol
    description: sets order, <fifo> or <lifo>

methods:
  - type: dump
    description: outputs all messages and clears them
  - type: clear
    description: clears the stack
  - type: n
    description: outputs number of elements in right outlet
  - type: fifo
    description: set order to 'fifo'
  - type: lifo
    description: set order to 'lifo'
  - type: show
    description: opens [text] window
  - type: hide
    description: closes [text] window



draft: false
---