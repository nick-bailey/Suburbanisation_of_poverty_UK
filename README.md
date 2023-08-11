# Suburbanisation_of_poverty_UK
Repository for code used in paper on 'Housing and welfare reform, and the suburbanisation of poverty in UK cities, 2011-20'. The analysis is in two parts covering private rental listings data and Housing Benefit claims data. 

## Private rental sector listings data (Zoopla plc)
These data are accessed under licence from the Urban Big Data Centre (www.ubdc.ac.uk). Other UK-based academics can access the data there while the licence remains current. The code to produce Figures 1-3 in the paper is here: 'PRS and suburbs - Zoopla data - resub.Rmd'.

In addition to open datasets noted in the code (postcode to higher area lookups; small area population data), there are a number of other inputs used in the analysis: 
* postcode to Broad Rental Market Areas (BRMAs) lookup: https://github.com/nick-bailey/Postcode-to-BRMA-lookup
* Local Housing Allowance Rates for BRMAs, 2012 onwards: https://github.com/nick-bailey/LHA-rates-for-BRMAs
* file measuring LSOA centrality within TTWAs kindly provided by MengLe Zhang: https://raw.githubusercontent.com/MengLeZhang/decentralisationPaper2

## Housing Benefit claims data (open)
These are open data access through APIs and downloads from various webpages. The code to produce Figures 4-6 in the paper is here: 'PRS and suburbs – HBen data – v6.Rmd'

There are two preparatory stages: 
* Housing Benefit data prepared using code in this repository: https://github.com/nick-bailey/StatXplore-Housing-Benefit-claims
* Small Area Population Estimates data prepared using code in this repository: https://github.com/nick-bailey/Small-area-populations-2011-on
