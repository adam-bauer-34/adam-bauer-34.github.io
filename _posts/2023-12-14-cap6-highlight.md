---
layout: post
title: Merging Physics and Economics for Climate Policy
description: A new research highlight on my climate-economics work.
date: 2023-12-14 15:01:35 +0300
image: '/images/blog-images/cap6-highlight/cap6-artsy.png'
tags: [climate-risk, cap6, climate-economics]
---

[*This article has been reproduced with permission from the University of Illinois Department of Physics website. Check out the other research highlights here!*](https://physics.illinois.edu/research/highlights)

# Merging Physics and Economics for Climate Policy

Climate change has the capacity to severely disrupt the global economy and cause immense harm to human wellbeing. The sixth assessment report issued by the Intergovernmental Panelon Climate Change (IPCC) warns as much: if we do not take more immediate action to abate CO2 emissions, we are on track for [“climate hell”](https://news.un.org/en/story/2023/09/1141082).

Perhaps surprisingly, economists have been in near-agreement (a historical rarity) on how to solve climate change: tax carbon dioxide emissions. The logic is simple: climate change is caused by unintended consequences of market activity, which can be remedied by [making polluters pay for the damages they cause](https://en.wikipedia.org/wiki/Pigouvian_tax). If we make polluters pay for the CO2 they emit via a tax, the story goes, they’ll have a strong incentive to decarbonize.

[A recent working paper I lead-authored](https://www.cesifo.org/en/publications/2023/working-paper/carbon-dioxide-risky-asset) asks the natural follow-up question: where do we set the tax? This debate has raged in climate-economics since the 1990s, when the first integrated climate-economic model was published in [*Science*](https://www.science.org/doi/10.1126/science.258.5086.1315). Its recommendation? Start with a low carbon tax that increases steadily over time. Intuitively, one can reason this policy recommendation as follows: “If the energy system is a cruise ship, we need to slowly change course in order to avoid the eventual iceberg [dangerous levels of warming].”

This is compelling logic, but it has a number of flaws. For one, it assumes we know exactly where the iceberg is. Namely, that we know how much greenhouse gas will be emitted over the next few-hundred years, how much the climate warms in response to CO2 emissions, and the extent to which warming damages the economy. Suffice to say, [none of these are known with nearly as much precision](https://www.brookings.edu/wp-content/uploads/2021/09/Social-Cost-of-Carbon_Conf-Draft.pdf) as we’d like to know them. This introduces a myriad number of risks in the climate-economic system.

The second flaw is in the model itself: [the climate dynamics are grossly inaccurate](https://www.journals.uchicago.edu/doi/10.1086/713977). The climate module all but assumes that most of the warming occurs far in the future, which allows the economy time to implement a low and rising tax. If one uses a credible climate emulator, it turns out that the proverbial iceberg is not as far away as this model makes it seem.

These two outstanding issues of previous-generation climate-economic models — a neglect of risk and inaccurate physical climate dynamics — was the impetus behind my coauthors and I’s recent working paper. We formulated a next-generation climate-economic model, named the Carbon Asset Pricing model — AR6 (CAP6), that (i) systematically treats uncertainty, and (ii) uses a state-of-the-art climate emulator.

CAP6 is based on a simplified representation of risk commonly used in asset pricing. Initially, there is a large degree of uncertainty about the value of the asset, causing the investor to hedge; over time, more information is revealed, which alters investment decisions. The twist in CAP6 is that CO2 is the “asset”, and its “price” is the amount it damages the economy. Hence, damages start highly uncertain (and potentially catastrophic), and over time are revealed to the policymaker. This endows CAP6 with a systematic treatment of uncertainty, a considerable upgrade from previous-generation models.

Furthermore, we root each of our model components in the [latest climate-economic science presented by the IPCC](https://www.ipcc.ch/assessment-report/ar6/) — the United Nations’ authoritative science arm for climate change and policy. We use the most up-to-date estimates for future emissions pathways, climate response, and climate damage functions. This puts each of the model components of CAP6 in-line with the state-of-the-art in both climate science and economics.

We find that CAP6’s carbon tax flips the conventional wisdom on its head: our carbon tax starts high, almost 2.5x what previous models would suggest. The high initial price is a form of hedge against catastrophic damages; moreover, once a considerable amount of fossil fuel emissions are abated owing to the high initial tax, then the potential for future damages is also considerably lessened. The substantial net-benefits to present-day and future generations causes the tax to be high in the near-term.

Our second key finding is that the carbon tax declines in time. As the future system is comparatively less risky than the initial system (owing to abated fossil fuel emissions and learning about damages), and given that the price of abatement technologies declines over time, there is less need for a high tax to incentivize businesses and individuals to ditch their fossil fuel addiction for cleaner alternatives.

The findings of our work prove the previously dominant heuristic about climate policy — that a “slow change of course” is required to avoid climate disaster — to be inaccurate. Or, perhaps, we may now complete the logic: if the energy system is indeed an ocean liner, then only if we decisively turn the wheel now will we have time to avert a disaster, especially in the presence of uncertainty.

---

*This article is based on the working paper: Bauer, A. M., C. Proistosescu, G. Wagner. Carbon dioxide as a risky asset. CESifo Working Paper No. 10278, 2023.*

*The artwork in the thumbnail was produced by [Alisa Singer](https://www.alisasingerart.com/about) of [Environmental Graphiti](https://www.environmentalgraphiti.org/). It is her interpretation of the binomial tree of uncertainty that underpins the model structure of CAP6.*

*This work was supported by a National Science Foundation Graduate Research Fellowship (Grant No. DGE 21-46756), Columbia Business School, and the Gies College of Business Office of Risk Management and Insurance at the University of Illinois Urbana-Champaign.*