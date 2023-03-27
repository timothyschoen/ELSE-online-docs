--- 


title: graph~

pdcategory: Analysis

inlets:

  1st:
  - type: signal
    description: incoming signal to graph

outlets:

  1st:
  - type: signal
    description: input signal comes out here



methods:
  - type: size <float>
    description: buffer size in samples
  - type: skip <float>
    description: number of buffers to skip
  - type: bgcolor <f, f, f>
    description: background color in RGB
  - type: fgcolor <f, f, f>
    description: foreground color in RGB
  - type: width <float>
    description: set signal width
  - type: range <float, float>
    description: set min/max range
  - type: dim <float, float>
    description: set horizontal/vertical dimensions

flags:
  - type: -size <float>
    description: buffer size in samples (default 441, minimum 64)
  - type: -skip <float>
    description: buffer skip (default 10)
  - type: bgcolor <f, f, f>
    description: background color in RGB (default 223 223 223)
  - type: fgcolor <f, f, f>
    description: foreground color in RGB (default 0 0 0)
  - type: width <float>
    description: set signal width (default 1)
  - type: -range <float, float>
    description: set lower and upper graph range (default -1 1)
  - type: -dim <float, float>
    description: set horizontal/vertical dimensions (default 200 140)

draft: false
---