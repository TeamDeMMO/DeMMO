+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 1  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = false

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = "calc(100vh - 70px)"

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "DeMMO 2016"
  #content = "I am center aligned :smile:"
  align = "center"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  # overlay_color = "#f7f0e7"  # An HTML color value.
   overlay_img = "slider/caitlin2016.jpg"  # Image path relative to your `static/img/` folder.
  # overlay_filter = 0.5  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  # cta_label = "Book an Appointment"
  # cta_url = "#booking"
  # cta_icon_pack = "fas"
  # cta_icon = "graduation-cap"

[[item]]
  #title = "Left"
  content = "Classic Styles"
  #align = "left"

  # overlay_color = "#555"  # An HTML color value.
  overlay_img = "hair1.jpg"  # Image path relative to your `static/img/` folder.
  # overlay_filter = 0.5  # Darken the image. Value in range 0-1.

[[item]]
  #title = "Right"
  content = "Rich Colors"
  align = "right"

  #overlay_color = "#333"  # An HTML color value.
  overlay_img = "hair2.jpg"  # Image path relative to your `static/img/` folder.
  #overlay_filter = 0.5  # Darken the image. Value in range 0-1.
  
  [[item]]
  #title = ""
  content = "Cool Tones"
  align = "left"

  #overlay_color = "#333"  # An HTML color value.
  overlay_img = "hair3.jpg"  # Image path relative to your `static/img/` folder.
  #overlay_filter = 0.5  # Darken the image. Value in range 0-1.
+++
