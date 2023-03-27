--- 


title: spectrograph~

pdcategory: UI

inlets:

  1st:
  - type: signal
    description: incoming signal to graph
  - type: bang
    description: graphs when rate is 0





methods:
  - type: size <f>
    description: sets FFT size
  - type: db <f>
    description: non-0 sets to dB amp scale
  - type: log <f>
    description: non-0 sets to log frequency scale
  - type: dim <f,f>
    description: set horizontal/vertical dimensions
  - type: rate <f>
    description: sets graph rate in ms

flags:
  - type: -size <f>
    description: FFT size (default 1024, min 128)
  - type: -db <f>
    description: non-0 sets to dB amp scale (default linear)
  - type: -log <f>
    description: non-0 sets to log frequency scale (default linear)
  - type: -dim <f,f>
    description: set horizontal/vertical dimensions (default 300 140)
  - type: -rate <float>
    description: sets graph rate in ms (default 100)

draft: false
---