--- 


title: keyboard

pdcategory: UI

inlets:

  1st:
  - type: float
    description: MIDI Note value
  - type: list <f,f>
    description: MIDI Note and Velocity values
  2nd:
  - type: float
    description: velocity of MIDI note value

outlets:

  1st:
  - type: list <f,f>
    description: MIDI Note and Velocity values



methods:
  - type: on <list>
    description: list MIDI Notes to be on with velocity of 127
  - type: off <list>
    description: list MIDI Notes to be off with velocity of 0
  - type: set <float, float>
    description: set note (pitch/velocity) without output
  - type: width <float>
    description: set key width
  - type: height <float>
    description: set keyboard height
  - type: oct <float>
    description: transpose octaves up or down
  - type: 8ves <float>
    description: set number of octaves
  - type: lowc <float>
    description: set number of lowest C (e.g. 4 = C4)
  - type: norm <float>
    description: set velocity normalization
  - type: toggle <float>
    description: sets toggle mode on <1> of off <0>
  - type: flush
    description: flushes hanging Note On keys
  - type: send <symbol>
    description: sets send symbol
  - type: receive <symbol>
    description: sets receive symbol

flags:
  - type: -width <float>
    description: width in pixels (default 17)
  - type: -height <float>
    description: height in pixels (default 80)
  - type: -oct <float>
    description: number of octaves (default 4)
  - type: -lowc <float>
    description: number of lowest C (default 3  that is "C3")
  - type: -tgl
    description: sets to toggle mode (default non toggle)
  - type: -norm <float>
    description: velocity normalization value (default 0)
  - type: -send <symbol>
    description: sets send symbol (default 'empty')
  - type: -receive <symbol>
    description: sets receive symbol (default 'empty')

draft: false
---