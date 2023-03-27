--- 


title: routeall

pdcategory: Data Management

inlets:

  1st:
  - type: anything
    description: any message to be routed completely
  2nd:
  - type: float
    description: set element number to match (default 0)

outlets:

  1st:
  - type: anything
    description: if an input message matches an argument, the corresponding outlet sends that message
  2nd:
  - type: anything
    description: any unmatched message

arguments:
  - type: anything
    description: arguments to match the 1st element of a message





draft: false
---