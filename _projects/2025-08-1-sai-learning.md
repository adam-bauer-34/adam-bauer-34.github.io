---
title: Inferring Stratospheric Aerosol Injection Climate Response Inequality
date: 2025-08-01 08:01:35 +0300
subtitle: Data assimilation | Risk analysis | Uncertainty
image: '/images/project-images/sai_angle_explainer.png'
---

# Project goal
If stratospheric aerosol injection (SAI) were ever deployed, one of the main concerns would be: are the benefits being equally distributed? SAI would cool the planet, but it wouldn't perfectly undo CO<sub>2</sub> warming: some regions would cool more than others. A simple way to summarize this is the SAI "angle parameter," which measures how far the regional SAI response departs from a perfect offset of CO<sub>2</sub>. Climate models disagree on its value, so the natural hope is that we'd learn it by watching the climate respond during a deployment. The question is how fast.

This project builds a hierarchy of models to answer that question. The issue is that, in the real world, we don't know the CO<sub>2</sub> response either: the climate's sensitivity to CO<sub>2</sub> has to be estimated *at the same time* as the SAI response, using the same observations. Past studies sidestepped this by working within a single climate model, where the CO<sub>2</sub> response is effectively known. Starting from a simple regression model, we find that three knobs control how fast we learn: how big the SAI signal is, how big the confounding CO<sub>2</sub> signal is, and how similar the two signals look over time.

We then test this intuition with a Bayesian data assimilation model. Surprisingly (at least to me!), the "obvious" strategy of ramping up SAI quickly to get a big signal early barely helps. A slowly ramped program with 0.5 °C of cooling leads to about thes same level of uncertainty as a fast program with *twice* the cooling. Cutting CO<sub>2</sub> emissions also speeds up learning: end-of-century uncertainty is ~40% larger under high emissions than low emissions. This gives an unusual argument for pairing any SAI program with emissions cuts: it makes the inequality of SAI's benefits easier to detect.

# Abstract
Cooling the climate with stratospheric aerosol injection (SAI) would imperfectly substitute for lowering global temperatures by reducing atmospheric carbon dioxide (CO<sub>2</sub>): some regions will cool more or less in an SAI and CO<sub>2</sub>-forced climate than in a CO<sub>2</sub>-only forced climate. This heterogeneity in the regional response to SAI is not well-constrained, but could be better constrained during an SAI deployment using observations of the climate response to SAI. Here, we formulate a hierarchy of models to understand the rate at which uncertainty in the inequality of the regional response to SAI &mdash; summarized by the SAI &ldquo;angle parameter&rdquo; &mdash; would decline during an SAI deployment. We identify three factors that influence learning about the angle parameter: (1) the SAI forcing magnitude, (2) the CO<sub>2</sub> forcing magnitude, and (3) the temporal covariance between the two forcings. We find that higher SAI signal accelerates learning, while higher CO<sub>2</sub> forcing and temporal covariance between the SAI and CO<sub>2</sub> forcings dampen learning. Numerical simulations suggest that the impact of the CO<sub>2</sub> forcing magnitude and covariance structure between SAI and CO<sub>2</sub> forcings on angle parameter uncertainty resolution is larger than the impact of the SAI forcing magnitude. This indicates that limiting CO<sub>2</sub> emissions and slowly ramping up SAI would result in the most favorable conditions for detecting inequalities in SAI benefits. We close by discussing how these results could influence coupled choices about CO<sub>2</sub> mitigation and SAI policy, as well as SAI scenario design.

# Working paper and citation
[Link to paper](/files/papers/sai-learning/BCK_InferringSAIInequality_Submitted.pdf) (submitted to *Environmental Research Letters*).

# Collaborators
[B. B. Cael](https://geosci.uchicago.edu/people/b-b-cael/) and [David Keith](https://davidkeith.earth/).

# Project code
All source code for this project can be found on [my Github](https://github.com/adam-bauer-34/learning_sai).

# Presentations
- American Geophysical Union Annual Meeting, 2025