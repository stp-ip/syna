+++
date = "2020-04-08"
fragment = "resumic"
weight = "110"
background = "light"

#file = "my-resume.json"

[general]
  attribution = true # Show attribution to Syna and Resumic in footer - default is false
  sort = true # Sort subsections by startDates, levels and more. Activities might be grouped in previous/present or by visual similarity - default is true
  meta = true # Show some metadata as footer - default is true
  disposition = true # Show disposition - default is true
  details = "full" # Default is full can be "full", "collapsed", "bare"
  image_only = false # Show only an image for entities if available - default is false

  [general.highlights]
    icon = "fas fa-search" # Default is empty

  [general.mapbox]
    # Strip from commits and invalidate after each run
    key = ""

[personal]
  show = true # Show persoanlly identifying information - default is false
  extend = true # Additionally show full personally identifying information including birthplace, relationshipStatus etc.
  phone = true # Show phone number in personal section - default is false
  email = true # Show email in personal section - default is false
  birthday = true # Show birthday in personal section - default is false
  postal = true # Show postal address in personal section - default is false

[education]
  group_primary = true # Group primary education items under "Primary Education" - default is false
  group_secondary = true # Group secondary education items under "Secondary Education" - default is false
  show_primary = true # Default is true
  show_secondary = true # Default is true

  [education.courses]
    show = true # Default is false
    icon = "fas fa-book" # Default is empty
+++
