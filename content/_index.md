---
title: "Psychological Characteristics of Leaders (PsyCL)"
description: ""
layout: single
---

The Leader Psychological Characteristics data set is a collection of at-a-distance derived cognitive and personality values attained through analysis of spoken words. This project provides scores on both [Leadership Trait Analysis](https://socialscience.net/docs/LTA.pdf) and Operational Code Analysis. You can find the disaggregated data with suggestions on how to aggregate them below. If you would like to see a selection of aggregated data, find that in the table of contents under the DATA section.

# Full Data Set

* You can find the full disaggregated data [**_HERE_**](https://raw.githubusercontent.com/JELambert/Psych_Agg/master/data/csv/speech_level.csv)

These data are at the speech level. Some leaders have multiple speeches in a single day. This data contains over 54 million words!

### Please cite the following when referencing the data.

* Mark Schafer, Joshua E. Lambert, Psychological Characteristics of Leaders (PsyCL): A New Data Set, Foreign Policy Analysis, Volume 18, Issue 2, April 2022, orac008, https://doi.org/10.1093/fpa/orac008


Please note that these data are only the raw counts of components of the different variables. In order for these data to be used, you must conduct calculations to convert these raw counts to variables. In addition, you are likely to need to aggregate multiple speech acts to your unit of analysis. Some of the processes for aggregation and calculation are discussed below. While it is possible to use the speech act itself as a unit of analysis (the raw counts still need to be converted to variables), note that many speech acts simply do not have enough verbal material to produce meaningful numbers. Therefore, we recommend some aggregation strategy that combines multiple speech acts.

## Aggregation Package

In order to manage the data set in its disaggregated form you must choose a unit of analysis and sum the columns based on this selection.  From these raw totals you can perform the proper mathematical operations to achieve valid scores of LTA and OpCode. To facilitate users with the tools needed to achieve this aggregation I have generated a python package that does the computations.
* You can find this package on my GitHub [**_HERE_**](https://github.com/JELambert/Psych_Agg) with installation and example usage.

If you use a tool outside of python, the formulae for each of these operations are also provided in text format on the FAQ page.
