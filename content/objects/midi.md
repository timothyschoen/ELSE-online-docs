--- 


title: midi

pdcategory: MIDI

inlets:

  1st:
  - type: float
    description: raw MIDI data to record
  - type: bang
    description: external clock tick

outlets:

  1st:
  - type: float
    description: raw MIDI data stream from a MIDI file
  2nd:
  - type: bang
    description: sent at the end of a sequence

arguments:
  - type: symbol
    description: a MIDI or text file to load

methods:
  - type: loop <float>
    description: non-0 sets to loop mode
  - type: record
    description: starts recording raw MIDI input
  - type: play
    description: start playing sequence
  - type: start
    description: sets to synced mode and expects clock ticks (bangs)
  - type: stop
    description: stops recording/playing and goes back to start
  - type: pause
    description: pauses recording/playing
  - type: continue
    description: continues recording/playing
  - type: speed <float>
    description: sets a reading speed in % of original
  - type: dump
    description: outputs the MIDI data stream at once
  - type: panic
    description: flushes hanging notes
  - type: clear
    description: clears sequence from the object
  - type: save <symbol>
    description: saves to a MIDI file

flags:
  - type: -loop
    description: sets the loop mode

draft: false
---