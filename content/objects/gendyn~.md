--- 


title: gendyn~

pdcategory: Signal Generators



outlets:

  1st:
  - type: signal
    description: dynamic stochastic synthesis output



methods:
  - type: n <float>
    description: set number of points (default 12)
  - type: frange <f, f>
    description: set minimum and maximum frequencies (default 220, 440)
  - type: freq_step <float>
    description: set maximum frequency step in % (default 50)
  - type: amp_step <float>
    description: set maximum amplitude step in % (default 25)
  - type: interp <float>
    description: sets interpolation mode (default 1, linear)
  - type: seed <float>
    description: sets seed, no float sets unique internal (default)
  - type: dist <f, f, f, f>
    description: sets distributions and parameters, see [pd distributions]

flags:
  - type: -n <f>
    description: 
  - type: -frange <f f>
    description: 
  - type: -freq_step <f>
    description: 
  - type: -amp_step <f>
    description: 
  - type: -interp <f>
    description: 
  - type: -seed <f>
    description: 
  - type: -dist <f f f f>
    description: 

draft: false
---