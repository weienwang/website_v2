+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 1  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = 5000

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = "350px"

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "Welcome to Wei's website"
  content = "When pain meets movement in the brain."
  align = "center"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color = "#666"  # An HTML color value.
  overlay_img = "headers/iStock-sky.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "My Github"
  cta_url = "https://github.com/weienwang"
  cta_icon_pack = "fab"
  cta_icon = "github-square"


[[item]]
  title = ""
  content = "Virtual Reality combined with EEG"
  align = "right"

  overlay_color = "#555"  # An HTML color value.
  overlay_img = "brain.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0  # Darken the image. Value in range 0-1.


+++
