--- 


title: unmerge

pdcategory: Data Management

inlets:

  1st:
  - type: anything
    description: a message whose elements get unmerged
  2nd:
  - type: size <float>
    description: number of elements in a group

outlets:

  1st:
  - type: anything
    description: the extra elements of the message
  2nd:
  - type: anything
    description: the bits of the unmerged message

arguments:
  - type: float
    description: number of outlets from 2-512 (default 2), there's an extra outlet for the extra elements
  - type: float
    description: elements number size per outlet (default 1)



flags:
  - type: -trim
    description: trims the selector

draft: false
---