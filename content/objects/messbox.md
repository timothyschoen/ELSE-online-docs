--- 


title: messbox

pdcategory: UI

inlets:

  1st:
  - type: bang
    description: outputs the message
  - type: anything
    description: sets messages with "$1" "$2", etc and outputs them

outlets:

  1st:
  - type: anything
    description: messages



methods:
  - type: set <anything>
    description: sets message
  - type: append
    description: appends to the message
  - type: dim <f, f>
    description: sets width and height
  - type: fontsize <float>
    description: sets font size
  - type: bold
    description: non-0 sets to bold
  - type: -bgcolor <f, f, f>
    description: sets background color
  - type: fgcolor <f, f, f>
    description: sets text color

flags:
  - type: -fontsize <float>
    description: font size
  - type: -size <f, f>
    description: size
  - type: -fgcolor <f, f, f>
    description: foreground color
  - type: -bgcolor <f, f, f>
    description: background color
  - type: -bold
    description: non-0 sets to bold

draft: false
---