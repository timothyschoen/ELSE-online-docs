--- 


title: pitch2note

pdcategory: Converters

inlets:

  1st:
  - type: float/list
    description: MIDI pitch value(s)
  2nd:
  - type: anything/list
    description: user defined scales

outlets:

  1st:
  - type: symbol/list
    description: note name(s)



methods:
  - type: chromatic
    description: sets to chromatic mode
  - type: sharp
    description: sets to sharp mode
  - type: flat
    description: sets to flat mode

flags:
  - type: -unicode
    description: sets to unicode mode
  - type: -list
    description: sets to list output mode

draft: false
---