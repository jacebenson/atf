+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 16 # Order that this section will appear.

title = "Contribute"
subtitle = ""

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "navy"
  
  # Background gradient.
  gradient_start = "DarkGreen"
  gradient_end = "ForestGreen"
  
  # Background image.
  # image = "image.jpg"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  text_color_light = true

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["20px", "0", "20px", "0"]

[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++

First of all, thanks for thinking of contributing to this project.  You're Awesome! 😍

We welcome contributions to ATF by everyone.  

## How to report a problem

Please search [issue tracker](https://github.com/jacebenson/atf/issues) before creating a new issue (problem or an improvement request).  Feel Free to add issues related to the project.

If you feel that you can fix or implement it yourself, please read a few paragraphs below to learn how to submit your changes.

## Submitting Changes

- Comment on the issue so others know you are working on the issue.
- Fork the project
- Install your fork on your Personal Developer Instance (PDI) with credientials (so you have write access)
- Create Branch `something-descriptive`
- Install necessary plugins for the test (e.g. CSM tests would require CSM to be installed)
- Ensure you are in the `ATF` scope
- Create the test for this issue
- Associate the test to the logical test suite
- Test your test in your PDI
- Commit your changes
- Create a Pull Request
