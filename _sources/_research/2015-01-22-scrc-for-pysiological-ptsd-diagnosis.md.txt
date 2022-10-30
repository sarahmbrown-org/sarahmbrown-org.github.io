---
layout: page
title: A Sparse Combined Regression-Classification Formulation for Learning a Physiological
  Alternative to Clinical Post-Traumatic Stress Disorder Scores
date: 2015-01-22 15:29:44.000000000 -08:00
type: jetpack-portfolio
published: true
status: publish
categories: []
tags: []
meta:
  bitly_url: http://2smb.link/1INEQdM
  bitly_hash: 1INEQdM
  bitly_long_url: http://www.sarahmbrown.org/?post_type=jetpack-portfolio&p=440
  _edit_last: '1'
  _publicize_twitter_user: "@BrownSarahM"
  _wpas_mess: 'Project page for my AAAI15 paper on learning formulation for PTSD diagnosis:
    http://2smb.link/1INEQdM'
  _wpas_done_all: '1'
  _wpas_skip_5078444: '1'
  _wpas_skip_5078449: '1'
author:
  login: smb@sarahmbrown.org
  email: smb@sarahmbrown.org
  display_name: Sarah Brown
  first_name: Sarah
  last_name: Brown
excerpt: "An applied machine learning AAAI-15 paper on a method for learning a scoring
  function for PTSD diagnosis from peripheral physiology measurements that maintains
  important properties without being subject to the same weaknesses of the 'gold standard'
  score produced by a clinical interview.  We present the problem as a slightly modified
  learning task from a typical setting, define desired properties of the method and
  propose a sparse combined classification-regression loss function for learning.
  "
gallery:
  - [code, fas fa-code, /files/SCRCforPTSDcode.zip]
  - [paper, fas fa-file, /papers/Brown_SCRCforPTSD_AAAI2015.pdf]
  - [poster, fas fa-image, /files/SCRCforPTSD_AAAI2015_poster.pdf]
---


Current diagnostic methods for mental pathologies, including Post-Traumatic Stress Disorder (PTSD), involve a clinician-coded interview, which can be subjective. Heart rate and skin conductance, as well as other peripheral physiology measures, have previously shown utility in predicting binary diagnostic decisions. The binary decision problem is easier, but misses important information on the severity of the patient’s condition. This work utilizes a novel experimental set-up that exploits virtual reality videos and peripheral physiology for PTSD diagnosis. In pursuit of an automated physiology-based objective diagnostic method, we propose a learning formulation that integrates the description of the experimental data and expert knowledge on desirable properties of a physiological diagnostic score. From a list of desired criteria, we derive a new cost function that combines regression and classification while learning the salient features for predicting physiological score. The physiological score produced by Sparse Combined Regression-Classification (SCRC) is assessed with respect to three sets of criteria chosen to reflect design goals for an objective, physiological PTSD score: parsimony and context of selected features, diagnostic score validity, and learning generalizability. For these criteria, we demonstrate that Sparse Combined Regression-Classification performs better than more generic learning approaches.

<!---
# Downloads:
[gallery link="file" columns="4" ids="446,444,443,595"]
&nbsp;
&nbsp;
Related Posts:
[display-posts include_excerpt="false" tag="aaai15" wrapper="ul"] --->
