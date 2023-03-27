--- 


title: grain.live~

pdcategory: Effects

inlets:

  1st:
  - type: signal
    description: signal input to be granulated
  - type: bang
    description: plays an event of cloud grains
  2nd:
  - type: float
    description: number of grains in the event (default 16, min 1, max 256)

outlets:

  1st:
  - type: signal
    description: left channel output
  2nd:
  - type: signal
    description: right channel output



methods:
  - type: dur <f>
    description: sets cloud event duration in ms (default 500)
  - type: sync <f>
    description: non-0 sets to synchronous mode (default 0)
  - type: size <f, f>
    description: sets min/max grain sizes in ms (default 50 to 450)
  - type: transp <f, f>
    description: sets min/max transposition in cents (default -1200 to 1200)
  - type: pan <f, f>
    description: sets left/right pan boundaries (default -1 to 1)
  - type: pos <f, f>
    description: sets min/max position in delay line (default 0 to 1)
  - type: amp <f, f>
    description: sets min/max amplitude values (default 0.1 to 1)
  - type: rev <float>
    description: sets probability in % of grain being reversed (default 0)
  - type: env <any>
    description: envelope type (sin, hann, tri, gauss) or function list
  - type: autotune <f>
    description: non-0 autotunes to a given scale (default 0)
  - type: scale <list>
    description: scale to autotune to in cents (default equal temperament)

flags:
  - type: -n <float>
    description: (number of grains)
  - type: -dur <f>
    description: 
  - type: -size <f, f>
    description: 
  - type: -picth <f, f>
    description: 
  - type: -autotune <f>
    description: 
  - type: -pan <f, f>
    description: 
  - type: -amps <f, f>
    description: 
  - type: -scale <list>
    description: 
  - type: -base <f>
    description: 
  - type: -rev <float>
    description: 
  - type: -env <any>
    description: 
  - type: -length <f>
    description: delay length in ms (default 5000)
  - type: -sync
    description: 

draft: false
---