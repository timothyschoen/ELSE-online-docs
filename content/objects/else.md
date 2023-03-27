--- 


title: else





outlets:

  1st:
  - type: list
    description: ELSE version (major, minor, bugfix, status, status number)
  2nd:
  - type: list
    description: Pd version (major, minor, bugfix)
  3rd:
  - type: list
    description: Pd flavor information

arguments:
  - type: float
    description: non-0 prevents printing on the terminal when loading

methods:
  - type: about
    description: prints library information on the terminal
  - type: version
    description: outputs version information as a list



draft: false
---