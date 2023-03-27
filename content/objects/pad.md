--- 


title: pad

pdcategory: UI



outlets:

  1st:
  - type: list
    description: list of coordinates (x, y)
  - type: click <float>
    description: report mouse button press <1> and release <0>



methods:
  - type: dim <f, f>
    description: set dimension (horizontal and vertical)
  - type: width <float>
    description: set width
  - type: height <float>
    description: set height
  - type: color <f, f, f>
    description: set RGB color

flags:
  - type: -dim <f, f>
    description: set horizontal and vertical dimensions (default 127, 127)

draft: false
---