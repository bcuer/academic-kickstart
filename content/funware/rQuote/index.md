+++
title = "Feature selection of longitudinal biomarkers in multivariate joint models for longitudinal and multi-state processes"

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date = 2019-07-15T14:24:00
#date_end = 2019-07-15T14:42:00
all_day = true

# Schedule page publish date (NOT talk date).
publishDate = 2017-01-01T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = []

# Location of event.
location = "Leuven, Belgium"

# Name of event and optional event URL.
event = "ISCB"
event_url = "https://kuleuvencongres.be/iscb40"

# Abstract. What's your talk about?
abstract = ""

# Summary. An optional shortened abstract.
summary = "Joint model for <b>multiple longitudinal</b> outcomes, <b>multiple events</b>, with the occurrence of <b>intermediate events</b> and <b>Bayesian shrinkage</b>."

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
url_slides = "ISCB_2019.pdf"

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

This work is motivated by a study at the Erasmus University Medical Center in the Netherlands on patients who received a Left Ventricular Assist Device (LVAD) after heart failure. These patients may experience multiple and potentially successive complications during follow-up, such as thrombosis and embolism which may increase their risk of dying. To reduce these risks, treating physicians follow these patients closely and collect repeated marker measurements for their liver and kidney function, both before and after LVAD intervention. Their primary research goals are to understand better how these biomarkers are associated with the risk of each complication and how LVAD intervention changes the dynamics between these associations, to better guide their decision making with respect to LVAD intervention. 

In this context, the joint modeling framework is a popular choice in addressing such objectives. However, while there has been a lot of work towards extensions of the classic joint modeling framework, such as multivariate joint models, joint models for a longitudinal outcome and a multi-state process and Bayesian shrinkage selection for the association structure in joint models, a unified approach allowing for all these features simultaneously has yet to be studied. Furthermore, investigating the performance of Bayesian shrinkage methods in terms of feature selection in highly correlated settings has not received a lot of attention. 

We therefore propose a flexible multivariate joint model for longitudinal and multi-state processes that includes LVAD intervention as a time-varying covariate in both the multivariate longitudinal and multi-state sub-models. We further allow for different association structures between the longitudinal marker and the transition-specific intensities, while allowing for baseline characteristics' effects to differ for each transition. To determine the most appropriate functional forms we use informative global-local shrinkage priors on the regression coefficients that correspond to the covariates of the transition-specific intensities. 

The results suggest that the use of the global-local shrinkage priors improves the estimation and identification of association parameters and functional forms respectively, in highly correlated settings and especially for transitions with low event rates.