+++
date = "2020-04-08"
fragment = "resumic"
weight = 140
background = "white"

file = "my-resume.json"

[general]
  attribution = true # Show attribution to Syna and Resumic in footer - default is false
  sort = true # Sort subsections by startDates, levels etc. - default is true
  personal = true # Show personally identifying information - default is false
  meta = true # Show some metadata as footer - default is true

  [general.highlights]
    icon = "fas fa-search" # Default is empty

  [general.mapbox]
    key = "pk.eyJ1Ijoic3RwLWlwIiwiYSI6ImNrOHNveDc3YjBqc2EzcXRsdW5pM255Y3kifQ.glkZKu-lLKFtEwsZZt4uuQ"

  [general.content]
    details = "full" # Default is full can be "full", "collapsed", "bare"

[education]
    group_primary = true # Group primary education items under "Primary Education" - default is false
    group_secondary = true # Group secondary education items under "Secondary Education" - default is false
    show_primary = true # Default is true
    show_secondary = true # Default is true

  [education.courses]
    show = true # Default is false
    icon = "fas fa-book" # Default is empty

+++
