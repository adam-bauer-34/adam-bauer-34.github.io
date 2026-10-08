---
title: Changes in Global and Regional Extreme Temperatures Over Land - An Extreme Value Theory Perspective
date: 2026-09-09 18:29:00 +0300
subtitle: Data science | Risk analysis | Statistics
image: '/images/project-images/heatwave.png'
---

# Project goal
When people ask whether heat waves are getting worse, they are usually asking two questions at once. The first is whether the entire temperature distribution has shifted warmer, which makes hot days hotter without anything changing about the shape of the distribution. The second is whether the hottest days of the year are warming *faster* than average days.

This project leverages extreme value theory to answer this question. The first step is to rigorously verify that the generalized extreme value distribution is a fit-for-purpose statistical model for annual maximum/minimum temperature data. Surprisingly, despite wide use in the climate literature, the GEV hasn't been verified as applicable to extreme temperature data. Our test confirms that, yes, the GEV is able to be applied in the context of extreme temperatures.

We then use the GEV to explore how the distribution of extreme temperatures is changing and whether climate models capture the distributional features we find in reanalysis. Most interestingly to me, we find that there are large fractions of the land surface (20-40%!) where biases in the *variability* of temperature, rather than the mean, dominate biases in extreme temperatures. (Previous studies put the fraction of the land surface where variability is the dominant source of uncertainty at 0%.)

# Abstract
Heat waves are among the most damaging consequences of climate change, yet how the distribution of extreme temperatures is changing remains unclear. Here, we show that the generalized extreme value distribution is fit-for-purpose to analyze extreme temperatures over land. We find that there is no statistically significant trend in global maximum temperatures relative to the mean in the reanalysis record. However, we do find statistically significant regional trends: about 14% of the land surface has a statistically significant positive trend relative to the mean, and about 17% of the land surface has a significant negative trend. We show that climate models struggle to reproduce the distributional characteristics of extreme temperatures found in reanalysis, other than the distributional mean. Finally, we find that biases in the variability, rather than the mean-state, of the extreme temperature distribution dominate biases in projections of extreme temperature risk over large fractions of the land surface.

# Working paper and citation
[Link to paper](/files/papers/extreme-temperatures-evt/BS2C-Manuscript.pdf) (submitted to *Geophysical Research Letters*)

_Citation_: Bauer, A. M., V. Sapkota, I. Baxter, T. A. Shaw, B. B. Cael. Changes in Global and Regional Extreme Temperatures Over Land: An Extreme Value Theory Perspective. (in review)

# Collaborators
[Vikrant Sapkota](https://climate.uchicago.edu/people/vikrant-sapkota/), Ian Baxter, [Tiffany A. Shaw](https://geosci.uchicago.edu/people/tiffany-shaw/), and [B. B. Cael](https://geosci.uchicago.edu/people/b-b-cael/).

# Project code
All source code for this project can be found on [my Github](https://github.com/adam-bauer-34/gev-heat-waves)

# Presentations
- American Geophysical Union Annual Meeting, 2026
- American Meterological Society Annual Meeting, 2027