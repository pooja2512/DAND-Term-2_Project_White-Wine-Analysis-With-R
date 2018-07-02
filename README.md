# White-Wine-Analysis-With-R

This project was completed as part of the course requirements of Udacity's [Data Analyst Nanodegree](https://in.udacity.com/) certification

## Overview
White wine is a wine whose colour can be straw-yellow, yellow-green, or yellow-gold. It is produced by the alcoholic fermentation of the non-coloured pulp of grapes, which may have a skin of any colour. White wine has existed for at least 2500 years

Citation Request:
  This dataset is public available for research. The details are described in [Cortez et al., 2009]. 
  
P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. 
  Modeling wine preferences by data mining from physicochemical properties.
  In Decision Support Systems, Elsevier, 47(4):547-553. ISSN: 0167-9236.

Available at: [@Elsevier] http://dx.doi.org/10.1016/j.dss.2009.05.016
                [Pre-press (pdf)] http://www3.dsi.uminho.pt/pcortez/winequality09.pdf
                [bib] http://www3.dsi.uminho.pt/pcortez/dss09.bib
                
[View Code Here](https://github.com/pooja2512/DAND-Term-2_Project_White-Wine-Analysis-With-R/blob/master/whitewine_exploratory_analysis.rmd)
                
The inputs include objective tests (e.g. PH values) and the output is based on sensory data (median of at least 3 evaluations made by wine experts). Each expert graded the wine quality between 0 (very bad) and 10 (very excellent).

- 1.Title: Wine Quality 
- 2.Sources:Created by: Paulo Cortez (Univ. Minho), Antonio Cerdeira, Fernando Almeida, Telmo Matos and Jose Reis (CVRVV) @ 2009
- 3.Number of Instances: 4898. 
- 4.Number of Attributes: 13 attributes

Attribute information:

Input variables (based on physicochemical tests):

- 1 - fixed acidity (tartaric acid - g / dm^3)
- 2 - volatile acidity (acetic acid - g / dm^3)
- 3 - citric acid (g / dm^3)
- 4 - residual sugar (g / dm^3)
- 5 - chlorides (sodium chloride - g / dm^3
- 6 - free sulfur dioxide (mg / dm^3)
- 7 - total sulfur dioxide (mg / dm^3)
- 8 - density (g / cm^3)
- 9 - pH
- 10 - sulphates (potassium sulphate - g / dm3)
- 11 - alcohol (% by volume)
- Output variable (based on sensory data): 
   12 - quality (score between 0 and 10)

**Description of attributes:**

- 1 - fixed acidity: most acids involved with wine or fixed or nonvolatile (do not evaporate readily)
- 2 - volatile acidity: the amount of acetic acid in wine, which at too high of levels can lead to an unpleasant, vinegar taste
- 3 - citric acid: found in small quantities, citric acid can add 'freshness' and flavor to wines
- 4 - residual sugar: the amount of sugar remaining after fermentation stops, it's rare to find wines with less than 1 gram/liter and wines with greater than 45 grams/liter are considered sweet
- 5 - chlorides: the amount of salt in the wine
- 6 - free sulfur dioxide: the free form of SO2 exists in equilibrium between molecular SO2 (as a dissolved gas) and bisulfite ion; it prevents microbial growth and the oxidation of wine
- 7 - total sulfur dioxide: amount of free and bound forms of S02; in low concentrations, SO2 is mostly undetectable in wine, but at free SO2 concentrations over 50 ppm, SO2 becomes evident in the nose and taste of wine
- 8 - density: the density of water is close to that of water depending on the percent alcohol and sugar content
- 9 - pH: describes how acidic or basic a wine is on a scale from 0 (very acidic) to 14 (very basic); most wines are between 3-4 on the pH scale
- 10 - sulphates: a wine additive which can contribute to sulfur dioxide gas (S02) levels, wich acts as an antimicrobial and antioxidant
- 11 - alcohol: the percent alcohol content of the wine

Output variable (based on sensory data): 

- 12 - quality (score between 0 and 10)

## Statistical Analyses
Examinations of central tendency and spread
Data visualization of univariate, bivarte and multivariate relationships
Correlation testing

## Technologies Used
R, R Markdown
Libraries: ggplot2,dplyr,GGally,gridExtra,RColorBrewer,ggcorrplot,ggExtra
R studio

## Key Findings

- Four Major attributes to decide the Quality of wine are  Alcohol,Residual Sugar,Density,Acidity Levels.
- With increasing Quality alcohol content increases but residual sugar decreases therefore high quality wines are more alcoholic and less sweet.
- Density has inverse correlation with quality it decreases with increasing quality ratings.
- Acidity levels of white wine ranges between 2.8 to 3.5
- For high acidity levels Content of residual sugar increases and alcohol content decreases.Higher the acidity in a wine, the more residual sugar the wine can have.
