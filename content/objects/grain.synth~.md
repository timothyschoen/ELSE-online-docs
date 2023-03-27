--- 


title: grain.synth~

pdcategory: Effects

inlets:

  1st:
  - type: bang
    description: plays <dur> of pitched clouds
  2nd:
  - type: float
    description: density (number of grains)

outlets:

  1st:
  - type: signal
    description: left channel output
  2nd:
  - type: signal
    description: right channel output



methods:
  - type: n <float>
    description: number of grains in event cloud (default 16, min 1, max 256)
  - type: set <symbol>
    description: sets table name with waveform
  - type: sync <f>
    description: non-0 sets to synchronous mode (default 0)
  - type: dur <f>
    description: sets cloud event duration in ms (default 500)
  - type: size <f, f>
    description: sets min/max grain sizes in ms (default 50 to 450)
  - type: pitch <f, f>
    description: sets min/max pitch values in MIDI (default 30 to 90)
  - type: pan <f, f>
    description: sets left and right pan boundaries (default -1 to 1)
  - type: amp <f, f>
    description: min/max amplitude values (default 0.1 to 1)
  - type: env <any>
    description: envelope type (sin, hann, tri, gauss) or function list
  - type: autotune <f>
    description: non-0 autotunes to a given scale (default 0)
  - type: scale <list>
    description: scale to autotune to in cents (default equal temperament)
  - type: base <f>
    description: sets scale's base MIDI pitch (default 60)

flags:
  - type: -n <float>
    description: 
  - type: -t <symbol>
    description: table name
  - type: -dur <f>
    description: 
  - type: -size <f, f>
    description: 
  - type: -pitch <f, f>
    description: 
  - type: -pan <f, f>
    description: 
  - type: -amps <f, f>
    description: 
  - type: -autotune <f>
    description: 
  - type: -scale <list>
    description: 
  - type: -base <f>
    description: 
  - type: -env <any>
    description: 
  - type: -sync
    description: 

draft: false
---