---
title: "Snow water equivalents from snow depths: improvements of the DeltaSNOW model"
collection: talks
type: "Talk"
permalink: /talks/egu_2022_swe_trends
venue: "EGU General Assembly 2022"
date: 2022-05-26
location: "Vienna, Austria"
---

[Further info](https://doi.org/10.5194/egusphere-egu22-2326)

Snow water equivalent (SWE) is probably the most important snowpack property, but due to various reasons it has been measured by far less frequently and continuously than, e.g., snow depth (HS). Recent modelling efforts led to ΔSNOW, a semi-empirical approach to derive daily SWE exclusively from consecutive HS series.

The ΔSNOW model - freely available as part of the R-package “nixmass” - builds on basic snow physics and needs seven parameters. If available, those should be fitted using SWE measured at the respective HS observation site(s), otherwise a standard set of parameters is provided, which was calibrated with data from the Alps. In the current model version, the parameters are kept unchanged over time. New-snow density and the maximum density model layers can reach are among the parameters. For natural snow, those vary significantly from day to day and during the winter season, also site specifics like, e.g., altitude influence them.

With this contribution the restriction of fixed density parameters in the ΔSNOW model is probed. Improvements might be achieved if new-snow density was made dependent on the amount of freshly fallen snow, rather than on altitude, date or region. The model-intrinsic maximum snow density could probably be improved if it was increased by the age of the respective snow layers as well as the overburden mass of snow. All validation experiments were performed with SWE and HS data from the Alps and from Germany. The latter comprising a huge high quality data set not only from mountainous regions but also from lowlands and maritime regions. The ΔSNOW model`s ability to simulate daily SWE outperforms other models of comparable complexity also in these areas, even more with adjusted density parameters.