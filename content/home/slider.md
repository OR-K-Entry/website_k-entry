+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 1  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = 4000

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = "calc(100vh - 70px)"

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "Data accessibility"
  content = "Putting data in the hands of providers"
  align = "center"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color = "#666"  # An HTML color value.
  overlay_img = "ela-app.png"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.6  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "Early Learning Alliance Application"
  cta_url = "https://djanderson07.shinyapps.io/ela-shiny/"
  #cta_icon_pack = "fas"
  #cta_icon = "graduation-cap"

[[item]]
  title = "Geographical variation"
  content = "Exploring Access to Pre-K services"
  align = "center"

  overlay_color = "#666"  # An HTML color value.
  overlay_img = "or-map.png"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.6  # Darken the image. Value in range 0-1.
  cta_label = "See the project"
  cta_url = "https://github.com/OR-K-Entry/ec-providers"

[[item]]
  title = "Publicly-available data"
  content = "Pooling community-level data on health, economics, and demographics"
  align = "center"

  overlay_color = "#666"  # An HTML color value.
  overlay_img = "data-documentation.png"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.6  # Darken the image. Value in range 0-1.
  cta_label = "Get access"
  cta_url = "https://github.com/OR-K-Entry/k-entry"
+++
