+++
title = "Handling informative dropout in longitudinal analysis of health-related quality of life"

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date = 2018-10-26T14:24:00
#date_end = 2018-10-26T14:42:00
all_day = true

# Schedule page publish date (NOT talk date).
publishDate = 2017-01-01T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = []

# Location of event.
location = "Dublin, Ireland"

# Name of event and optional event URL.
event = "ISOQOL"
event_url = "https://www.isoqol.org"

# Abstract. What's your talk about?
abstract = ""

# Summary. An optional shortened abstract.
summary = "Application on data from the oesophageal cancer clinical trial PRODIGE5/ACCORD17"

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
url_slides = "2018-10_ISOQOL.pdf"

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Links (optional).
url_pdf = ""
url_video = ""
url_code = ""

# Demo talk page uses LaTeX math.
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Right"
+++

<b>Aims</b>
Health-related quality of life (HRQoL) has become a crucial endpoint in cancer clinical trials but missing data can compromise its longitudinal analysis. Missingness can depend only on observed characteristics or HRQoL (MAR assumption), or additionally on unobserved HRQoL (MNAR assumption).
Our objective was to explore and compare several approaches to longitudinally model HRQoL data with potentially informative drop-out (subsequent to HRQoL deterioration) in the PRODIGE5/ACCORD17 clinical trial.

<b>Methods</b>
In this trial, HRQoL were assessed using the EORTC QLQ-C30 questionnaire in 267 patients with advanced oesophageal cancer receiving FOLFOX or fluorouracil-cisplatin.
We have first used linear mixed models (LMMs) which produce unbiased estimates under the MAR assumption. Assuming a MNAR assumption, we have considered the joint distribution of the HRQoL score and the missingness process. It decomposes in two ways leading to pattern-mixture models (PMMs) or selection models (SMs). PMMs were mixtures of the conditional distribution of the HRQoL score given the pattern of drop-out weighted by the probability of drop-out in each pattern. SMs factored the joint distribution into the HRQoL score distribution and the conditional distribution of the missingness process given the HRQoL scores.

<b>Results</b>
At baseline and at 12 months (6th assessment), the compliance was 119/134 (89%) and 48/101 (48%) in the FOLFOX arm and 120/133 (90%) and 44/99 (44%) in the fluorouracil-cisplatin arm, respectively.
Using LMMs (MAR assumption), we have obtained estimates including time and arm effects.
Using the PMM approach (MNAR assumption), we have considered 6 patterns corresponding to the time of drop-out. The HRQoL score were modeled using a mixture of LMMs, thus we have calculated weighted estimates and compared them to the estimates from the LMM approach.
Using the SM approach, we have modeled the drop-out probability using a logistic regression depending on the last (observed) and current (unobserved) HRQoL scores. In this case, the unobserved score coefficient allowed to test the MNAR assumption.

<b>Conclusions</b>
Although PMMs and SMs account for informative drop-out contrary to LMMs, they also rely on untestable modelling assumptions. This work has allowed to better understand them. We have also illustrated the advantages/drawbacks of PMMs and SMs regarding clinical interpretation.
