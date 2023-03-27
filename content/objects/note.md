--- 


title: note

pdcategory: UI

inlets:

  1st:
  - type: set <anything>
    description: sets a new text note





methods:
  - type: set <anything>
    description: sets a new text note
  - type: append <anything>
    description: appends a message to the note
  - type: prepend <anything>
    description: prepends a message to the note
  - type: font <symbol>
    description: sets font name
  - type: size <float>
    description: sets font size
  - type: bold <float>
    description: non-0 sets to bold
  - type: italic <float>
    description: non-0 sets to italic
  - type: underline <float>
    description: non-0 sets underline
  - type: just <float>
    description: sets justification (0; left, 1; center, 2; right)
  - type: width <float>
    description: sets width in pixels
  - type: color <f, f, f>
    description: sets RGB text color (values from 0 to 255)
  - type: bgcolor <f, f, f>
    description: sets RGB background color (values from 0 to 255)
  - type: bg <float>
    description: background flag (0 suppresses background)
  - type: outline <float>
    description: non-0 sets an outline
  - type: receive <symbol>
    description: sets receive symbol

flags:
  - type: -font <symbol>
    description: 
  - type: -bold
    description: 
  - type: -italic
    description: 
  - type: -size <float>
    description: default patch's
  - type: -just <float>
    description: default 0
  - type: -color <f, f, f>
    description: default 0 0 0
  - type: -bgcolor <f, f, f>
    description: default 255 255 255
  - type: -bg
    description: 
  - type: -outline
    description: 
  - type: -note <anything>
    description: sets note (default "note")
  - type: -underline
    description: 
  - type: -receive <symbol>
    description: default 'empty'
  - type: -width <float>
    description: default 0

draft: false
---