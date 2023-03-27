--- 


title: dec2frac

pdcategory: Data Math

inlets:

  1st:
  - type: list
    description: decimal value(s)

outlets:

  1st:
  - type: list
    description: converted fractional value(s)

arguments:
  - type: float
    description: conversion resolution (min 10)

methods:
  - type: res <float>
    description: set conversion resolution

flags:
  - type: -list
    description: sets to list mode (output fraction as a list)

draft: false
---