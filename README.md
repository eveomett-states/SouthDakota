# License
This data was generated using data from the Redistricting Data Hub.  Any use of this project shall also comply with restrictions on use of data and attribution requirements set forth in the Redistricting Data Hub terms and conditions found at: [https://redistrictingdatahub.org/terms-and-conditions/](https://redistrictingdatahub.org/terms-and-conditions/).

Use of this project is further governed by the terms of the [Creative Commons Attribution Noncommercial 4.0 International](https://creativecommons.org/licenses/by-nc/4.0/legalcode.en)

# South Dakota Json and Shapefile

This shapefile was processed by Professor Ellen Veomett and her student Ananya Agarwal using the corresponding jupyter notebook.  As part of the cleaning process, precincts were nested within counties and small rook adjacencies (under 30.5 m) were changed to queen adjacencies.

# **Sources**
@author: eveomett AI for Redistricting, USF All data retrieved 06/01/24:

Obtain the following data from Restricting Data Hub

[Population data](https://redistrictingdatahub.org/dataset/south-dakota-block-pl-94171-2020-by-table/): based on the decennial census at the Census Block level on 2020 Census Redistricting Data

[State House District data](https://redistrictingdatahub.org/dataset/2021-south-dakota-state-house-of-representatives-approved-plan/): 2021 State House Approved Plan

[State Senate District data](https://redistrictingdatahub.org/dataset/2021-south-dakota-state-senate-approved-plan/): 2021 State Senate Approved Plan

[2020 election data](https://redistrictingdatahub.org/dataset/vest-2020-south-dakota-precinct-and-election-results/)**:**  VEST 2020 South Dakota precinct and election results

[2018 election data](https://redistrictingdatahub.org/dataset/vest-2018-south-dakota-precinct-and-election-results/)**:**  VEST 2018 South Dakota precinct and election results

[2016 election data](https://redistrictingdatahub.org/dataset/vest-2016-south-dakota-precinct-and-election-results/)**:**  VEST 2016 South Dakota precinct and election results

[2020 County data](https://redistrictingdatahub.org/dataset/south-dakota-county-pl-94171-2020/): from 2020 Census Redistricting Data (P.L. 94-171) Shapefiles

# **Processing**

Data were cleaned and aggregated in the corresponding jupyter notebook using MGGG’s python library [maup](https://github.com/mggg/maup). 

# **Metadata**

Below is a brief description of each of the listed variables in the attribute table of the VTD shapefile:

- `STATEFP20`: State FIPS code
- `COUNTYFP20`: County FIPS code
- `VTDST20`: Voting tabulation district FIPS code
- `NAME20`: Voting tabulation district name
- `SEND`: State Senate district for 2021 State Senate Adopted Plan
- `HDIST`: State House district for 2024 State House of Representatives Districts Plan
- `TOTPOP`: Total population in 2020 Census
- `NH_WHITE`: White, non-hispanic, population in 2020 Census
- `NH_BLACK`: Black, non-hispanic, population in 2020 Census
- `NH_AMIN`: American Indian and Alaska Native, non-hispanic, population in 2020 Census
- `NH_ASIAN`: Asian, non-hispanic, population in 2020 Census
- `NH_NHPI`: Native Hawaiian and Pacific Islander, non-hispanic, population in 2020 Census
- `NH_OTHER`: Other race, non-hispanic, population in 2020 Census
- `NH_2MORE`: Two or more races, non-hispanic, population in 2020 Census
- `HISP`: Hispanic population in 2020 Census
- `H_WHITE`: White, hispanic, population in 2020 Census
- `H_BLACK`: Black, hispanic, population in 2020 Census
- `H_AMIN`: American Indian and Alaska Native, hispanic, population in 2020 Census
- `H_ASIAN`: Asian, hispanic, population in 2020 Census
- `H_NHPI`: Native Hawaiian and Pacific Islander, hispanic, population in 2020 Census
- `H_OTHER`: Other race, hispanic, population in 2020 Census
- `H_2MORE`: Two or more races, hispanic, population in 2020 Census
- `VAP`: Total voting age population in 2020 Census
- `HVAP`: Hispanic voting age population in 2020 Census
- `WVAP`: White, non-hispanic, voting age population in 2020 Census
- `BVAP`: Black, non-hispanic, voting age population in 2020 Census
- `AMINVAP`: American Indian and Alaska Native, non-hispanic, voting age population in 2020 Census
- `ASIANVAP`: Asian, non-hispanic, voting age population in 2020 Census
- `NHPIVAP`: Native Hawaiian and Pacific Islander, non-hispanic, voting age population in 2020 Census
- `OTHERVAP`: Other race, non-hispanic, voting age population in 2020 Census
- `2MOREVAP`: Two or more races, non-hispanic, voting age population in 2020 Census
- `ATG18D`: Number of votes for 2018 Democratic attorney general candidate
- `ATG18R`: Number of votes for 2018 Republican attorney general candidate
- `AUD18D`: Number of votes for 2018 Democratic auditor candidate
- `AUD18R`: Number of votes for 2018 Republican auditor candidate
- `GOV18D`: Number of votes for 2018 Democratic gubernatorial candidate
- `GOV18R`: Number of votes for 2018 Republican gubernatorial candidate
- `GOV18O`: Number of votes for 2018 other party's gubernatorial candidate
- `HAL16D`: Number of votes for 2016 Democratic US House candidate
- `HAL16R`: Number of votes for 2016 Republican US House candidate
- `HAL18D`: Number of votes for 2018 Democratic US House candidate
- `HAL18R`: Number of votes for 2018 Republican US House candidate
- `HAL18O`: Number of votes for 2018 other party's US House candidate
- `HAL20D`: Number of votes for 2020 Democratic US House candidate
- `HAL20R`: Number of votes for 2020 Republican US House candidate
- `PRE16D`: Number of votes for 2016 Democratic presidential candidate
- `PRE16R`: Number of votes for 2016 Republican presidential candidate
- `PRE16O`: Number of votes for 2016 other party's presidential candidate
- `PRE20D`: Number of votes for 2020 Democratic presidential candidate
- `PRE20R`: Number of votes for 2020 Republican presidential candidate
- `PRE20O`: Number of votes for 2020 other party's presidential candidate
- `PUC16D`: Number of votes for 2016 Democratic Public Utilities Commissioner candidate
- `PUC16R`: Number of votes for 2016 Republican Public Utilities Commissioner candidate
- `PUC18D`: Number of votes for 2018 Democratic Public Utilities Commissioner candidate
- `PUC18R`: Number of votes for 2018 Republican Public Utilities Commissioner candidate
- `PUC20D`: Number of votes for 2020 Democratic Public Utilities Commissioner candidate
- `PUC20R`: Number of votes for 2020 Republican Public Utilities Commissioner candidate
- `PUC20O`: Number of votes for 2020 other party's Public Utilities Commissioner candidate
- `SOS18D`: Number of votes for 2018 Democratic Secretary of State
- `SOS18R`: Number of votes for 2018 Republican Secretary of State
- `SPL18D`: Number of votes for 2018 Democratic Commissioner of School and Public Lands candidate
- `SPL18R`: Number of votes for 2018 Republican Commissioner of School and Public Lands candidate
- `TRE18D`: Number of votes for 2018 Democratic Treasurer
- `TRE18R`: Number of votes for 2018 Republican Treasurer
- `USS16D`: Number of votes for 2016 Democratic senate candidate
- `USS16R`: Number of votes for 2016 Republican senate candidate
- `USS20D`: Number of votes for 2020 Democratic senate candidate
- `USS20R`: Number of votes for 2020 Republican senate candidate

