---
title: "Snow Water Equivalents exclusively from Snow Heights and their temporal Change: The ΔSNOW.MODEL"
collection: talks
type: "Poster"
permalink: /talks/egu_2020_deltasnow
venue: "EGU General Assembly 2020"
date: 2020-05-06
location: "Vienna, Austria"
---

[Further info](https://doi.org/10.5194/egusphere-egu2020-11298)

Snow heights have been measured at lots of places over many years and decades, often at daily resolution. In many cases the data series have no gaps and are of high quality. In recent times, remote sensing provides more and more maps of snow heights, sometimes at high temporal frequency as well. However, most of these snow height data series lack information about snow water equivalents (SWEs), and they often come without sufficient meteorological data to run sophisticated, process-based snow models to simulate SWEs. Statistical SWE models, on the other hand, are subject to regional calibration parameters and cannot model SWEs of distinct days. Nevertheless, for many applications (hydrology, climatology, structural design,…) SWE-series are very valuable.

The ΔSNOW.MODEL presented, is a semi-empirical layer-model that simulates SWEs exclusively from snow heights and their temporal changes. It is computationally cheap and is provided as an easy-to-use R-package. Like statistical snow models, the ΔSNOW.MODEL does not need any meteorological input, but simulates more accurate SWE values: Statistical models typically show root mean square differences between observations and model values of 20-50 kg/m², biases of maximum seasonal SWE of +50 to +100 kg/m², and timing offsets for seasonal maximum SWE of -15 to 0 days. The ΔSNOW.MODEL reaches 15-30 kg/m², -20 to +20 kg/m², and -3 to +5 days, respectively. These scores are comparable with those of process based models, though they are calculated without the need of further meteorological or geographical data except snow height. Therefore, the ΔSNOW.MODEL can be used to assign highly reliable means and maxima of SWE as well as durations of high snow loads to long-term and historic snow height data, and it can simulate SWEs of distinct days with a comparatively high precision. In some (promising) respect the ΔSNOW.MODEL bridges the gap between process-based and statistical snow models.