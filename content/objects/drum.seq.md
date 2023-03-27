--- 


title: drum.seq

pdcategory: Triggers and Clocks

inlets:

  1st:
  - type: bang
    description: gets sequence value and moves to the next
  - type: list
    description: sets track, slot and status (no output)
  - type: float
    description: sets slot value and output tracks values

outlets:

  1st:
  - type: list
    description: track and slot value (indexed from 1)
  - type: bang
    description: when reaching the end of the sequence



methods:
  - type: track <list>
    description: sets track values (1st value sets track number)
  - type: goto <float>
    description: sets slot value
  - type: clear
    description: clears active cells (no output)
  - type: export <float>
    description: export tracks, no float exports all as an array
  - type: import <list>
    description: import contents as an array
  - type: tracks <float>
    description: sets number of tracks (clears data)
  - type: slots <float>
    description: sets number of slots (clears data)
  - type: size <float>
    description: sets cell size in pixels (clears data)
  - type: embed <float>
    description: non-0 save internal contents with the object
  - type: export <list>
    description: array of contexts via the "export" message

flags:
  - type: -tracks <float>
    description: sets tracks (default 2)
  - type: -slots <float>
    description: sets number of slots (default 8)
  - type: -size <float>
    description: sets cell size in pixels (default 20)
  - type: -embed
    description: sets embedding mode (default no embedding)

draft: false
---