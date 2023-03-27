--- 


title: order

pdcategory: Data Management

inlets:

  1st:
  - type: anything
    description: any number of elements to be split and ordered

outlets:

  1st:
  - type: list
    description: ordered lists, with the split elements preceded by index

arguments:
  - type: float
    description: number of elements to be ordered
  - type: float
    description: index offset

methods:
  - type: n <float>
    description: number of elements in each ordered list
  - type: offset <float>
    description: index offset



draft: false
---