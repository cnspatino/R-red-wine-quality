# R-red-wine-quality

This report explores data collected from 1599 red wine samples of the Portuguese Vinho Verde type around 2009. Eleven physiochemical properties were collected from each sample (input variables), along with a median quality rating from wine experts (target feature).  
  
This dataset is publically available for research. The details are described in [Cortez et al., 2009], cited below.   
  
  P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. 
  Modeling wine preferences by data mining from physicochemical properties.
  In Decision Support Systems, Elsevier, 47(4):547-553. ISSN: 0167-9236.  
  
  Available at: [@Elsevier] http://dx.doi.org/10.1016/j.dss.2009.05.016
                [Pre-press (pdf)] http://www3.dsi.uminho.pt/pcortez/winequality09.pdf
                [bib] http://www3.dsi.uminho.pt/pcortez/dss09.bib . 
    
  Description of variables:  
  Input variables (based on physicochemical tests):  
   1 - fixed acidity (tartaric acid - g / dm^3) - most acids involved with wine are fixed/nonvolatile    
   2 - volatile acidity (acetic acid - g / dm^3) - the amount of acetic acid in wine   
   3 - citric acid (g / dm^3) - found in small quantities; can add 'freshness' and flavor to wines  
   4 - residual sugar (g / dm^3) - the amount of sugar remaining after fermentation stops   
   5 - chlorides (sodium chloride - g / dm^3) - the amount of salt in the wine   
   6 - free sulfur dioxide (mg / dm^3) - the free form of SO2; prevents microbial growth and the oxidation of wine  
   7 - total sulfur dioxide (mg / dm^3) - amount of free and bound forms of S02  
   8 - density (g / cm^3) - the density of wine is close to that of water depending on percent alcohol and sugar content  
   9 - pH - describes how acidic or basic a wine is, most wines are between 3-4 on the pH scale   
   10 - sulphates (potassium sulphate - g / dm3) - a wine additive which can contribute to sulfur dioxide gas levels   
   11 - alcohol (% by volume) - the percent alcohol content of the wine   
  Output variable (based on sensory data):   
   12 - quality (score between 0 and 10)   
