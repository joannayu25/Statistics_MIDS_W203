# Reducing Crime - Final Project (Statistics for Data Science)
Joanna Yu, Vinicio De Sola, Sam Tosaria

W203 Tuesday 4pm Fall 2018

12/11/2018

## Introduction
Public policy is focused on maximizing the well-being of the population and reducing the harmful effects of crime on the society while ensuring equitable treatment of all residents within the justice system. Crime poses sustantial economic and intangible costs to the society. Based on The Bureau of Justice statistics and FBI data, the U.S. crime rate reached a broad peak between the 1970s through early 1990s and has declined significantly after that. The current crime rates are about the same as those in the 1960s. This is partly the result of a series of policies targeted at reducing crime rate. A good understanding of factors associated with crime is important for effective policymaking and resource allocation.

In this study, we will research the crime data for a selection of counties in North Carolina from the year 1987 to understand the determinants of crime and generate policy suggestions for the local or state governments.  

## About the Data
The dataset was first used in a study by Cornwell and Trumball, researchers from the University of Georgia and West Virginia University. The data used for this analysis is a single cross-section of original data, but the original study was based on a multi-year panel. The authors used panel data methods and instrumental variables to control for some types of omitted variables. In this study, we are restricted to ordinary least squares regression so we aim for causal estimates, while clearly explaining how we think omitted variables may affect our conclusions.

The dataset includes 25 variables that describe the various statistics of each county. The variables have been grouped by the following major categories: 

No. | Category | Fields
--- | ------------------- | ----------------------------------------------------
1 | Crime Rate | crmrte
2 | Crime Punishment | prbarr, prbconv, prbpris, avgsen
3 | Population | density, pctmin80, pctymle
4 | Economic | taxpc
5 | Geographic | county, west, central, urban
6 | Income | wcon, wtuc, wtrd, wfir, wser, wmfg, wfed, wsta, wloc
7 | Crime Type | mix
8 | Law Enforcement | polpc
9 | Time Period | year

Our final dataset contains 90 observations and 25 variables. In North Carolina, there is a total of 100 counties, thus our dataset covers 90% of all North Carolina. We must assume that the counties not included were selected at random, so our dataset is built from a random sample. If not, we know that there will be some biases in our results.

## Modeling Process and Conclusion
Please see [paper](./DeSola_Tosaria_Yu_lab3_Final.pdf).