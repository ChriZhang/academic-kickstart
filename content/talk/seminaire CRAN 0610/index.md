+++
title = "Contrôle sous contraintes en dimension infinie : application à l'équation de la chaleur"
date = 2022-10-06 # Schedule page publish date.
draft = false

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
time_start = 2022-10-06T14:00:00
#time_end = 2030-10-06T15:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Christophe Zhang"]

# Abstract and optional shortened version.
abstract = "De nombreuses applications font apparaître des problèmes de contrôle d'EDP avec des contraintes sur le contrôle (positivité, contrainte de masse, etc...). En vue d'implémentations possibles, les contraintes de type 'on/off' présentent un intérêt particulier, car elles visent à trouver des contrôles dont la forme est simple car binaire. Le problème type que je présenterai porte sur le contrôle approché de l'équation de la chaleur par des 'formes': à l'aide d'un terme source donné par la fonction caractéristique d'un ensemble (variable dans le temps, de mesure uniformément bornée), on cherche à emmener la solution près d'un état final donné. Par une approche qui combine relaxation et analyse convexe, et que j'illustrerai géométriquement, je montrerai comment l'on peut construire de tels contrôles, en les voyant comme des contrôles optimaux pour un problème de contrôle optimal bien choisi. On verra que l'approche peut se généraliser à de nombreux autres problèmes, notamment car il s'appuie sur un fait très général : les maximiseurs d'une fonction convexe sur un convexe compact contiennent au moins un point extrémal, ie un point qui sature les contraintes. Cela rejoint le phénomène dit 'bang-bang' en contrôle optimal : en dimension finie, il a été souvent observé que les contrôles optimaux (notamment les contrôles en temps minimal) saturent les contraintes qui leur sont imposées, et ont donc une forme plus simple (par exemple, une fonction constante par morceaux en temps). Le phénomène apparaît également en dimension infinie et nous verrons comment l'approche développée pour l'équation de la chaleur permet de l'étudier. "

# Name of event and optional event URL.
event = "Séminaire de l'équipe CO2, Centre de Recherche en Automatique de Nancy"
event_url = ""

# Location of event.
location = "Nancy"

# Is this a selected talk? (true/false)
selected = false

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["internal-project"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = ""
url_code = ""

# Does the content use math formatting?
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
  # Caption (optional)
 # caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Right"
+++

