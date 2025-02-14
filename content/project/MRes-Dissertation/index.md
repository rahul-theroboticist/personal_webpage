---
title: Human's Social Signals during Error Situations in Human-Robot Interaction
subtitle: My MSc by research (MRes) robotics dissertation
summary: Research dissertation completed as part of my postgraduate degree.  
authors: ["admin"]
tags:
- Human Robot Interaction
- Machine Learning
- Social Signals
- Error Situations
- ABB Yumi Robot
date: "2020-08-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Social Signals and Non-verbal behavioural cues (​Vinciarelli et al., 2012, p. 2) ​
  focal_point: Smart

links:
# - icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: 
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

During human-robot interactions, error situations caused by either the robot or
human often affects those interactions and may also lead to termination. One of the
variables the robots can analyse to recognize such error situations are the social
signals from the human interaction partner. We investigated the verbal and
non-verbal social signals that humans show while experiencing various error
situations in a human-robot interaction to find if the humans show the same social
signals or individual social signals. We manually annotated the multimodal social
signals of humans by using 50 participant’s audio-video data collected from a recent
human-robot interaction user study. With the audio-video recordings of 200 social
norms violations, 200 execution errors and 200 planning errors by the robot a total of
600 error situations were annotated. Later, we prepared multimodal datasets from
the manual annotations and used the datasets to train a rule learner PART, a Naive
Bayes classifier and a Random Forest classifier. We evaluated the classifiers with
10-fold cross validation and percentage-split validation techniques. The results of
this evaluation suggests the following: (1) The detection of different error situations
works well when the robot has seen the human before. (2) Overall, Random Forest
classifier and rule learner PART performed well for detecting different error situations
when the robot is interacting with known and unknown humans. (3) The humans
showed more social signals during the robot’s planning errors than in execution
errors and social norms violations. (4) The classification of social norms violations
mostly performed the worst but with some humans they were classified better than
execution errors suggesting that the humans don’t show the same social signals. We
also visualised the correlations between the social signals and the error types for
each participant. We compared those visualisations between the participants and we
found that the participants show individual social signals. We therefore conclude
from our results that humans experiencing error situations in a human-robot
interaction show individual social signals.

> Open access to the complete dissertation will be made availabe here once published in the university website.   
