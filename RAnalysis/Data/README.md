readme.md

# About:


### larval_survival

* Metadata columns:

  - **Parental_OA**, **Exposure OA**: represent categorical OA treatment as low, moderate, and high

  - **run**, **Date**, **Generation**, **Age**: self explanatory, run, generation, and date described in the main README for this repository


* Data columns

  - **Count**: the number of estimated larvae present in each replicate tank

  - **Destructive_sampling**: the total number of animals removed for microscopy counts and/or RR at the given Date and for the replicate tank

  - **Cumulative_destructive_sampling**: *This is critical!* Data here represent the cumulative
  number of animals removed *for the replicate tank and prior to the date/age in question*, these data are used to correct for removal in R
