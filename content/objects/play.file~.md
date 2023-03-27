--- 


title: play.file~

pdcategory: Buffers

inlets:

  1st:
  - type: bang
    description: (re)start playing the sample
  - type: float
    description: non-0 (re)starts playing, zero stops

outlets:

  1st:
  - type: signal
    description: the sample signal of channel $nth
  2nd:
  - type: bang
    description: a bang when finishing playing the sample

arguments:
  - type: float
    description: (optional) number of channels (max 64)
  - type: symbol
    description: the name of the file to open
  - type: float
    description: autostart <1; on, 0; off>
  - type: float
    description: loop <1; on, 0; off>

methods:
  - type: start
    description: (re)start playing the sample
  - type: stop
    description: stop playing the sample
  - type: open <symbol>
    description: opens a file with the symbol name (no symbol opens dialog box) and starts playing
  - type: set <symbol>
    description: sets a file to open next time it starts playing
  - type: loop <float>
    description: loop on <1> or off <0>

flags:
  - type: -loop
    description: turns loop mode on

draft: false
---