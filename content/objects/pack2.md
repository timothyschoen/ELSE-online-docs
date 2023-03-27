--- 


title: pack2

pdcategory: Data Management

inlets:

  1st:
  - type: bang
    description: outputs the stored list of elements

outlets:

  1st:
  - type: anything
    description: the message composed of the given elements

arguments:
  - type: anything
    description: the number of elements = the number of inlets. <f> or <symbol> — initial value

methods:
  - type: set <anything>
    description: the elements of a message update the inlet's value they are connected to and the subsequent inlets according to the remaining elements  it doesn't force an output
  - type: anything
    description: same as "set", but it forces an output



draft: false
---