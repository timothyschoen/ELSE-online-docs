--- 


title: store

pdcategory: Data Management

inlets:

  1st:
  - type: bang
    description: outputs element from sequence and goes forward
  - type: float
    description: sets index and outputs stored messages at index
  2nd:
  - type: anything
    description: messages to be stored in a sequence

outlets:

  1st:
  - type: anything
    description: the stored message
  2nd:
  - type: anything
    description: bang at the end of sequence or 'n' number of messages

arguments:
  - type: float
    description: float  non-0 sets to store elements with the patch

methods:
  - type: goto <float>
    description: sets index to output on next bang message
  - type: dump
    description: outputs all stored messages sequentially
  - type: clear
    description: clears all messages
  - type: n
    description: outputs number of elements in the right outlet
  - type: show
    description: opens [text] window
  - type: hide
    description: closes [text] window
  - type: click
    description: clicking on the object opens [store]'s window



draft: false
---