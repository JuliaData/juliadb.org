+++
title = "How JuliaDB Works"
date = 2018-08-08T00:00:00  # Schedule page publish date (not talk date).

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Shashi Gowda"]

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
# time_start = 2030-06-01T13:00:00
# time_end = 2030-06-01T15:00:00
all_day = true

# Location of event.
location = "JuliaCon 2018, London"

# Name of event and optional event URL.
event = "JuliaCon 2018"
event_url = "https://juliacon.org/2018/"

# Abstract. What's your talk about?
abstract = "JuliaDB is a pure Julia analytical database. It makes loading large datasets and playing with them easy and fast. JuliaDB needs to support a number of features: releational database operations, quickly parsing text files, parallel computing, data storage and compression.  This talk is a bottom-up look at the construction of JuliaDB. We will talk about the scope and implementation of underlying building block packages, namely IndexedTables, TextParse, Dagger, OnlineStats and PooledArrays."

# Summary. An optional shortened abstract.
#summary = "An example talk using Academic's Markdown slides feature."

# Is this a featured talk? (true/false)
featured = false

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Optional filename of your slides within your talk folder or a URL.
url_slides = ""

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Links (optional).
url_pdf = ""
url_video = "https://www.youtube.com/watch?v=pVNOf5kgpE4"
url_code = ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Right"
+++

{{% alert note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /alert %}}

Slides can be added in a few ways:

- **Create** slides using Academic's *Slides* feature and link using `url_slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://sourcethemes.com/academic/docs/writing-markdown-latex/).

Further talk details can easily be added to this page using *Markdown* and $\rm \LaTeX$ math code.
