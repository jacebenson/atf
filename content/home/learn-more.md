+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 20 # Order that this section will appear.

title = "What is this?"
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

This is a [scoped app](https://docs.servicenow.com/bundle/newyork-application-development/page/build/applications/concept/c_ApplicationScope.html) in ServiceNow to give administrators and Developers a faster Automated Testing implementation.

# Why?

- Simple single source for all tests
- Tests that work regardless of data in your system

# Can you elaborate on that?

Well ServiceNow originally didn't have any pre-canned tests to test the Out of Box offerings they had.  So that was the initial goal of this project.  As time's progressed, so has this project.  

Now ServiceNow does include some pre-canned tests, however they rely on administrators installing an plugin for each test suite.  [There](https://docs.servicenow.com/bundle/newyork-application-development/page/administer/auto-test-framework/reference/available-quick-start-tests.html) [are](https://docs.servicenow.com/bundle/newyork-governance-risk-compliance/page/administer/atf-quick-start-tests/reference/quick-start-tests-grc-policy-comp.html) [a](https://docs.servicenow.com/bundle/newyork-governance-risk-compliance/page/administer/atf-quick-start-tests/reference/quick-start-tests-grc-risk.html) [lot](https://docs.servicenow.com/bundle/newyork-performance-analytics-and-reporting/page/administer/atf-quick-start-tests/reference/quick-start-tests-dashboards.html) [of](https://docs.servicenow.com/bundle/newyork-it-business-management/page/administer/atf-quick-start-tests/reference/quick-start-tests-apm.html) [these](https://docs.servicenow.com/bundle/newyork-it-service-management/page/administer/atf-quick-start-tests/reference/quick-start-tests-im.html).

Additionally most of those tests rely on you to have either the original groups that came with the instance when it was initially stood up OR they depend on you to edit them.  So generally they don't even run today in most instances.
