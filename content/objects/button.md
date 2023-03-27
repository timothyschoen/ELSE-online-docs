--- 


title: button

pdcategory: UI

inlets:

  1st:
  - type: dim <f, f>
    description: sets horizontal and vertical size in pixels
  - type: size <float>
    description: sets both horizontal and vertical size in pixels
  - type: width <float>
    description: sets horizontal size in pixels
  - type: height <float>
    description: sets vertical size in pixels
  - type: bgcolor <f, f, f>
    description: sets background color in RGB
  - type: fgcolor <f, f, f>
    description: sets foreground color in RGB

outlets:

  1st:
  - type: float
    description: latch status (on=1 or off=0)



methods:
  - type: dim <f, f>
    description: sets horizontal and vertical size in pixels
  - type: size <float>
    description: sets both horizontal and vertical size in pixels
  - type: width <float>
    description: sets horizontal size in pixels
  - type: height <float>
    description: sets vertical size in pixels
  - type: bgcolor <f, f, f>
    description: sets background color in RGB
  - type: fgcolor <f, f, f>
    description: sets foreground color in RGB

flags:
  - type: -dim <float, float>
    description: x/y dimensions (default = 20, 20)
  - type: size <float>
    description: sets both horizontal and vertical size in pixels
  - type: -bgcolor <float, float>
    description: background color in RGB (default 255 255 255)
  - type: -fgcolor <float, float>
    description: foreground color in RGB (default 255 255 255)

draft: false
---