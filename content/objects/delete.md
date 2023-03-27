--- 


title: delete

pdcategory: Data Management

inlets:

  1st:
  - type: anything
    description: input message
  2nd:
  - type: float
    description: element number
  3rd:
  - type: float
    description: number of elements to delete

outlets:

  1st:
  - type: list
    description: remaining elements from the input message
  2nd:
  - type: list/bang
    description: deleted elements or bang when deleting fails

arguments:
  - type: float
    description: element index to delete from
  - type: float
    description: number of elements to delete





draft: false
---