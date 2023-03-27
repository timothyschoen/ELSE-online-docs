--- 


title: tabwriter~

pdcategory: Arrays and Tables

inlets:

  1st:
  - type: float/signals
    description: non-0 starts recording, 0 stops it
  - type: rec
    description: (re)starts recording
  - type: stop
    description: stops recording
  2nd:
  - type: signal
    description: signal to record into an array channel 'n'

outlets:

  1st:
  - type: signal
    description: output index we're recording into
  2nd:
  - type: bang
    description: when recording reaches the end of the array

arguments:
  - type: symbol
    description: array name (optional)
  - type: float
    description: channels to record (max 64)

methods:
  - type: set <symbol>
    description: sets array for recording signals
  - type: start <float>
    description: start point in ms (default 0)
  - type: end <float>
    description: end point in ms (default array's initial size)
  - type: range <f, f>
    description: sets start and end point range proportionally (from 0 to 1)
  - type: reset
    description: resets start/end from 0 to (current) array's size
  - type: continue <float>
    description: non-0 continue recording from where it last stopped
  - type: loop <float>
    description: non-0 enables loop recording, 0 disables it

flags:
  - type: -continue <f>
    description: 
  - type: -loop <f>
    description: 
  - type: -start <f>
    description: 
  - type: -end <f>
    description: 
  - type: -ch <f> (# of channels)
    description: 

draft: false
---