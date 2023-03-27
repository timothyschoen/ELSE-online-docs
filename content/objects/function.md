--- 


title: function

pdcategory: UI

inlets:

  1st:
  - type: float
    description: values from 0-1 are treated as indexes
  - type: list
    description: sets and outputs breakpoints function
  - type: bang
    description: outputs breakpoints function

outlets:

  1st:
  - type: list
    description: breakpoints function for [envgen~]/[function~]



methods:
  - type: i <float>
    description: indexes of table (function value is output)
  - type: set <list>
    description: sets breakpoints function
  - type: duration <float>
    description: resets overall duration
  - type: min <float>
    description: sets minimum graph boundary
  - type: max <float>
    description: sets maximum graph boundary
  - type: resize <float>
    description: sets new graph bounds according to min/max
  - type: height <float>
    description: sets height
  - type: width <float>
    description: sets width
  - type: fgcolor <f, f, f>
    description: sets RGB color of foreground
  - type: bgcolor <f, f, f>
    description: sets RGB color of background
  - type: send <symbol>
    description: sets send symbol
  - type: receive <symbol>
    description: sets receive symbol
  - type: init <float>
    description: non-0 sets to init mode

flags:
  - type: -height <float>
    description: (default 100)
  - type: -width <float>
    description: (default 200)
  - type: -send <symbol>
    description: (default none)
  - type: -receive <symbol>
    description: (default none)
  - type: -bgcolor <f, f, f>
    description: 
  - type: -fgcolor <f, f, f>
    description: 
  - type: -resize <float>
    description: 
  - type: -min <float>
    description: (default 0)
  - type: -max <float>
    description: (default 1)
  - type: -init
    description: 
  - type: -set <list>
    description: (default 0 1000 0)

draft: false
---