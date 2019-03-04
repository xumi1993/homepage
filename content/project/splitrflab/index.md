+++
title = "SplitRFLab"
date = 2019-03-03T22:33:40+08:00
draft = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Software"]

# Project summary to display on homepage.
summary = "A MATLAB GUI toolbox for receiver function analysis based on SplitLab"

# Slides (optional).
#   Associate this page with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Optional external URL for project (replaces project detail page).
external_link = ""

# Links (optional).
url_pdf = "http://link.springer.com/10.1007/s11589-016-0141-8"
url_code = ""
url_dataset = ""
url_slides = ""
url_video = ""
url_poster = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# links = [{icon_pack = "fab", icon="twitter", name="Follow", url = "https://twitter.com"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""

   # Show image only in page previews?
  preview_only = true

+++

We add new modules for receiver function (RF) analysis in SplitLab toolbox, which includes the manual RF analysis module, automatic RF analysis and related quality control modules, and H-k stacking module. The updated toolbox (named SplitRFLab toolbox), espe- cially its automatic RF analysis module, could calculate the RFs quickly and efficiently, which is very useful in RF analysis with huge amount of seismic data. China is now conducting the ChinArray project that plans to deploy thousands of portable stations across Chinese mainland. Our SplitRFLab toolbox may obtain reliable RF results quickly at the first time, which provide essentially new constraint to the crustal and mantle structures.

{{< figure src="workflow.jpg">}}
