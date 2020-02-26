+++
title = "Modèles conjoints avec risques concurrents pour l’analyse longitudinale de la qualité de vie en oncologie en présence de différents types de sorties d’études"

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date = 2019-10-11T14:24:00
#date_end = 2019-10-11T14:42:00
all_day = true

# Schedule page publish date (NOT talk date).
publishDate = 2017-01-01T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = []

# Location of event.
location = "Paris, France"

# Name of event and optional event URL.
event = "GDR « Statistiques et santé »"
event_url = "http://gdr-stat-sante.math.cnrs.fr/spip/spip.php?rubrique55"

# Abstract. What's your talk about?
abstract = ""

# Summary. An optional shortened abstract.
summary = ""

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
url_slides = "2019-10_GDR.pdf"

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

<b>Introduction</b>
La qualité de vie relative à la santé (QdV) est un critère majeur dans les essais cliniques en oncologie. Elle est évaluée par des questionnaires auto-administrés à différentes visites au cours de la prise en charge des patients. En présence de sorties d’étude informatives, l’analyse de l’évolution de la QdV par des modèles linéaires mixtes peut conduire à des résultats biaisés. Une solution consiste à la modéliser conjointement au risque de sortie d’étude. Le caractère informatif de la sortie d’étude peut cependant dépendre de sa cause.
L’objectif de ce travail est d’utiliser une modélisation conjointe qui distingue les sorties d’étude liées au décès (suspectées informatives) et les sorties d’étude « autres causes » (suspectées non informatives) à
travers un modèle à risques concurrents.

<b>Méthode</b>
Le modèle conjoint considéré se décompose en un modèle linéaire mixte à coefficients aléatoires pour la trajectoire du score de QdV et un modèle à risques concurrents pour le temps jusqu’à sortie d’étude, tous deux étant liés par une structure d’association correspondant au score courant de QdV.
Nous avons comparé ce modèle au modèle conjoint simple, i.e. sans distinction des causes de sortie d’étude, et au modèle linéaire mixte utilisé seul, i.e. sans prise en compte des sorties d’étude. Cette comparaison a été réalisée à travers une étude de simulations ainsi que sur des données d’essai clinique.


<b>Résultats</b>
Dans l’étude de simulations, nous avons considéré divers scénarios en faisant varier l’effet du traitement expérimental sur la QdV et sur le risque de sortie d’étude, l’intensité de l’association entre QdV et risque et enfin en faisant dépendre ou non de la cause de sortie d’étude l’effet du traitement sur le risque et l’intensité de l’association entre QdV et risque.
L’essai clinique randomisé ACCORD 17 a inclus 267 patients traités par radiochimiothérapie avec les traitements FOLFOX (expérimental) ou 5-fluorouracile-cisplatine (standard) pour un cancer de l’œsophage localement avancé. La QdV a été évaluée par le questionnaire EORTC QLQ-C30 à l’inclusion, à la fin de la radiothérapie, à 10 et 15 semaines, puis à 6, 12, 24 et 36 mois. A 36 mois, nous avons observé 242 sorties d’étude dont 69 que l’on a attribuées au décès (survenues dans les 6 mois après la dernière évaluation). Seule la fonction physique PF2 a été analysée qui est une des quatre dimensions du QLQ-C30 retenue comme critère secondaire de l’essai.


<b>Discussion</b>
Le modèle conjoint simple permet d’éviter des biais dans l’analyse de la QdV en oncologie en tenant compte de l’association entre niveau de QdV et risque de sortie d’étude. Le modèle conjoint avec risques concurrents est à ce jour plus difficile à mettre en œuvre mais il offre des perspectives intéressantes pour établir le caractère informatif ou non des sorties d’étude selon leur type et pour réduire les biais des estimations dans certains cas où un modèle conjoint simple ne suffit pas.
