--- 


title: gran.player~

pdcategory: Effects

inlets:

  1st:
  - type: bang
    description: (re)start playing the buffer from the beginning
  - type: float
    description: 1 is the same as "start", 0 is the same as "stop
  2nd:
  - type: float
    description: grain size in ms
  3rd:
  - type: float
    description: sets transposition in cents
  4th:
  - type: float
    description: sets transposition in cents

outlets:

  1st:
  - type: signal
    description: the buffer signal of the corresponding channel
  2nd:
  - type: bang
    description: a bang when finishing playing the buffer

arguments:
  - type: float
    description: (optional) channels (max 64)
  - type: symbol
    description: the name of the file to open
  - type: float
    description: autostart <1; on, 0; off>
  - type: float
    description: loop <1; on, 0; off>

methods:
  - type: open <symbol>
    description: opens a file with the symbol name (no symbol opens dialog box) and starts playing
  - type: start
    description: same as bang
  - type: stop
    description: stops and goes back to the beginning
  - type: size <float>
    description: sets gain size in ms
  - type: loop <float>
    description: loop on <1> or off <0>
  - type: range <f, f>
    description: sets sample's playing range (from 0 to 1)
  - type: pause
    description: pauses playing the buffer
  - type: continue
    description: unpauses and continues playing the buffer
  - type: reload
    description: reloads the file into the buffer and starts playing
  - type: set <symbol>
    description: sets a file to open (needs a reload message)

flags:
  - type: -speed <float>
    description: sets playing speed (default 100)
  - type: -transp <float>
    description: sets transposition in cents (default 0)
  - type: -size <float>
    description: sets grain size in ms (default 75)
  - type: -loop
    description: turns loop mode on (default off)
  - type: -range <float, float>
    description: sets sample range (

draft: false
---