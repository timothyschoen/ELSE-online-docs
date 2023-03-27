--- 


title: receiver

pdcategory: Data Management

inlets:

  1st:
  - type: symbol/list
    description: set the receive names
  - type: bang
    description: clears the receive names

outlets:

  1st:
  - type: anything
    description: any received messages (or receive names at bangs)

arguments:
  - type: list
    description: receive names

methods:
  - type: clear
    description: clears the receive names



draft: false
---