# License
This data was generated using data from the Redistricting Data Hub.  Any use of this project shall also comply with restrictions on use of data and attribution requirements set forth in the Redistricting Data Hub terms and conditions found at: [https://redistrictingdatahub.org/terms-and-conditions/](https://redistrictingdatahub.org/terms-and-conditions/).

Use of this project is further governed by the terms of the [Creative Commons Attribution Noncommercial 4.0 International](https://creativecommons.org/licenses/by-nc/4.0/legalcode.en)

# Virginia Json

This json and shapeifle were created by Professor Ellen Veomett and her student Ananya Agarwal using the corresponding jupyter notebook.  As part of the cleaning process, precincts were nested within counties and small rook adjacencies (under 30.5 m) were changed to queen adjacencies.

# **Sources**
All data retrieved 04/30/24:

Obtain the following data from Restricting Data Hub

[Population data](https://redistrictingdatahub.org/dataset/virginia-block-pl-94171-2020-by-table/): based on the decennial census at the Census Block level on 2020 Census Redistricting Data

[Congressional District data](https://redistrictingdatahub.org/dataset/2021-virginia-congressional-districts-approved-plan): 2021 virginia Congressional Districts plan enacted on 2/27/23

[State House District data](https://redistrictingdatahub.org/dataset/2021-virginia-house-of-delegates-districts-approved-plan/): 2021 State House Approved Plan

[State Senate District data](https://redistrictingdatahub.org/dataset/2021-senate-of-virginia-districts-approved-plan/): 2021 State Senate Approved Plan

[2021 election data](https://redistrictingdatahub.org/dataset/vest-2021-virginia-precinct-boundaries-and-election-results-shapefile/)**:**  VEST 2021 virginia precinct and election results

[2020 election data](https://redistrictingdatahub.org/dataset/vest-2020-virginia-precinct-boundaries-and-election-results-shapefile/)**:**  VEST 2020 virginia precinct and election results

[2018 election data](https://redistrictingdatahub.org/dataset/vest-2018-virginia-precinct-and-election-results/)**:**  VEST 2018 virginia precinct and election results

[2017 election data](https://redistrictingdatahub.org/dataset/vest-2017-virginia-precinct-boundaries-and-election-results-shapefile/)**:**  VEST 2017 virginia precinct and election results

[2016 election data](https://redistrictingdatahub.org/dataset/vest-2016-virginia-precinct-and-election-results/)**:**  VEST 2016 virginia precinct and election results

[2020 County data](https://redistrictingdatahub.org/dataset/virginia-county-pl-94171-2020/): from 2020 Census Redistricting Data (P.L. 94-171) Shapefiles

## Processing
Data were cleaned and aggregated in the corresponding jupyter notebook using MGGG’s python library [maup](https://github.com/mggg/maup).  

## Metadata

- `COUNTYFP20`: County FIPS code
- `LOCALITY20`: Locality FIPS Code
- `PRECINCT`: Precinct FIPS code
- `VTDST`: Voting Tabulation District FIPS code
- `CD`: Congressional district ID in 2021 congressional map, enacted on 2/27/23
- `SEND`: State Senate district for 2021 State Senate Approved Plan
- `HDIST`: State House district for 2024 State House Approved Plan
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
- `ATG17D`: Number of votes for 2017 Democratic attorney general candidate
- `ATG17R`: Number of votes for 2017 Republican attorney general candidate
- `ATG17O`: Number of votes for 2017 other party's attorney general candidate
- `ATG21D`: Number of votes for 2021 Democratic attorney general candidate
- `ATG21R`: Number of votes for 2021 Republican attorney general candidate
- `ATG21O`: Number of votes for 2021 other party's attorney general candidate
- `GOV17D`: Number of votes for 2017 Democratic gubernatorial candidate
- `GOV17R`: Number of votes for 2017 Republican gubernatorial candidate
- `GOV17O`: Number of votes for 2017 other party's gubernatorial candidate
- `GOV21D`: Number of votes for 2021 Democratic gubernatorial candidate
- `GOV21R`: Number of votes for 2021 Republican gubernatorial candidate
- `GOV21O`: Number of votes for 2021 other party's gubernatorial candidate
- `LTG17D`: Number of votes for 2017 Democratic lieutenant governor candidate
- `LTG17R`: Number of votes for 2017 Republican lieutenant governor candidate
- `LTG17O`: Number of votes for 2017 other party's lieutenant governor candidate
- `LTG21D`: Number of votes for 2021 Democratic lieutenant governor candidate
- `LTG21R`: Number of votes for 2021 Republican lieutenant governor candidate
- `LTG21O`: Number of votes for 2021 other party's lieutenant governor candidate
- `PRE16D`: Number of votes for 2016 Democratic presidential candidate
- `PRE16R`: Number of votes for 2016 Republican presidential candidate
- `PRE16O`: Number of votes for 2016 other party's presidential candidate
- `PRE20D`: Number of votes for 2020 Democratic presidential candidate
- `PRE20R`: Number of votes for 2020 Republican presidential candidate
- `PRE20O`: Number of votes for 2020 other party's presidential candidate
- `USS18D`: Number of votes for 2018 Democratic senate candidate
- `USS18R`: Number of votes for 2018 Republican senate candidate
- `USS18O`: Number of votes for 2018 other party's senate candidate
- `USS20D`: Number of votes for 2020 Democratic senate candidate
- `USS20R`: Number of votes for 2020 Republican senate candidate
- `USS20O`: Number of votes for 2020 other party's senate candidate
