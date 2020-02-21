---
abstract: "Nowadays stroke is a leading cause of adult disability. The Action Research Arm Test (ARAT) is a measure used in rehabilitation medicine to assess upper extremity performance. Motivated by a study conducted in Amsterdam and consists of 450 patients (mean age is 65 and mean follow-up visits is 6), our ultimate goal is to implement individualized dynamic predictions of ARAT in Gemstracker which is a software package consisting of different patient information collected during clinical research.


Different type of information is available at each visit such as patients characteristics, upper extremity function but also some other activity measurements. Physicians want to utilize all available data to predict ARAT measurements six months after stroke. Nowadays, predictions are based on simplistic approaches, such as regression, that ignore the dynamic nature of the disease. A popular framework to analyze repeated measures is the mixed-effects models. We aim to provide dynamic predictions for ARAT by extending the standard mixed-effects model to account for the special features of the data set.  


We, first, take into account that most of the covariates are time-dependent and measured with error.  Secondly, patients can be categorized in sub-groups that exhibit different progression rates, that is no recovery, full recovery, and middle recovery.  We propose a Bayesian latent class multivariate mixed-effects models to obtain individualized dynamic predictions of ARAT. We focus on how to quantify and evaluate those predictions. In particular, to quantify the accuracy of the predictions we will investigate different proper scoring rules. To evaluate those predictions we will use an internal validation procedure, where correct estimates of the proper scoring rules will be obtained using Bootstrap. 


A preliminary analysis comparing the standard mixed-effects model with a simple regression showed a 10% improvement in the average absolute error defined as the absolute difference between the true and observed ARAT.


Evidence-based algorithms for referral policies within stroke care pathways are lacking, and individual recovery profiles are hard to predict.  We will implement a decision support system that provides on-line transparent information to patients and caregivers at any time and any place about individual progress and predicted recovery potential."
 
all_day: true
authors: []
date: "2019-07-16"
#date_end: "2018-06-12T15:00:00Z"
event: International Society for Clinical Biostatistics
#event_url: https://example.org
featured: false
# links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
location: Leuven, Belgium
# math: true
# projects:
# - internal-project
# publishDate: "2017-01-01T00:00:00Z"
slides: 
summary: "" 
#tags: []
title: Dynamic prediction modelling in hand disorders after stroke using a latent class multivariate mixed model
#url_code: ""
#url_pdf: ""
url_slides: "ISCB_ARAT.pdf"
#url_video: ""
---
