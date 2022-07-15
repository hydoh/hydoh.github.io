---
layout: post
title: "Implementing the RL-DDM in hBayesDM"
author_profile: true
---

Hoyoung Doh, Sanghoon Kang, Jihyun Hur

# Introduction

Reinforcement learning (RL) models have been used to explain phenomena where feedback-based learning seem to play a role, including but not limited to Pavlovian conditioning, instrumental learning, and value-based decision-making. These models commonly posit a value assigned to a stimulus, an action or stimulus-action pair. The value-updating mechanism is a usually emphasized feature of these models.

# Candidate model selection

We used the eight candidate models used in Pedersen et al. (2017) for model selection. All RL-DDM models consist of both a learning component (RL), and a choice rule component (DDM) where the value difference between choices determine is reflected into Drift Rate (or the rate of evidence accumulation) that governs along with the Boundary Separation parameter (which determines the minimum amount of evidence needed for a decision to occur). In Pedersen et al. (2017), authors propose different ways in which differences in choice values determine Drite Rate and how Boundary Separation changes throughout the learning process. Specifically, depending on the model variation, additional parameters can change how choice values and time determine these two parameters:

# Model fitting process

# Model comparison process

# Model fitting results

# Model reliability evaluation

# Models implemented in the hBayesDM package

# How to run RL-DDMs in hBayesDM

```
a = 1
```

# Conclusion

# References
