--- 


title: datetime

pdcategory: Triggers and Clocks

inlets:

  1st:
  - type: bang
    description: outputs date and time

outlets:

  1st:
  - type: list
    description: time; hour, min, sec at bang or seed value via seed message
  2nd:
  - type: list
    description: date; year/month/day/weekday



methods:
  - type: seed
    description: get number of seconds since the beginning of the month to use it as a seed value



draft: false
---