# virginia Election Shapefile

This shapefile was processed by Professor Ellen Veomett and her student Ananya Agarwal.

# **Sources**
@author: eveomett AI for Redistricting, USF All data retrieved 04/30/24:

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

## Processing
Demographic data were aggregated from the block level to precincts using [MGGG’s proration software](https://github.com/mggg/maup). Congressional, house, and senate district IDs were assigned to precincts also using this package.

## Metadata
* `precinct`: Precinct name
* `locality`: Locality name
* `loc_prec`: Locality and precinct names
* `district`: Congressional district name
* `G18DHOR`: Number of votes for 2018 Democratic US House candidate
* `G18DSEN`: Number of votes for 2018 Democratic senate candidate
* `G18OSEN`: Number of votes for 2018 other senate candidates
* `G18RHOR`:  Number of votes for 2018 Republican US House candidate
* `G18RSEN`: Number of votes for 2018 Republican senate candidate
* `G17DGOV`: Number of votes for 2017 Democratic gubernatorial candidate
* `G17DLTG`: Number of votes for 2017 Democratic lieutenant governor candidate
* `G17DATG`: Number of votes for 2017 Republican attorney general candidate
* `G17DHOD`: Number of votes for 2017 Democratic House of Delegates candidate
* `G17RGOV`: Number of votes for 2017 Republican gubernatorial candidate
* `G17RLTG`: Number of votes for 2017 Republican lieutenant governor candidate
* `G17RATG`: Number of votes for 2017 Republican attorney general candidate
* `G17RHOD`: Number of votes for 2017 Republican House of Delegates candidate
* `G17OGOV`:  Number of votes for 2017 other gubernatorial candidates
* `G16DPRS`: Number of votes for 2016 Democratic presidential candidate
* `G16RPRS`: Number of votes for 2016 Republican presidential candidate
* `G16OPRS`: Number of votes for 2016 other presidential candidates
* `G16DHOR`: Number of votes for 2016 Democratic US House candidate
* `G16RHOR`: Number of votes for 2016 Republican US House candidate
* `G16OHOR`: Number of votes for 2016 other US House candidates
* `TOTPOP`: Total population 
* `NH_WHITE`: White, non-hispanic, population
* `NH_BLACK`: Black, non-hispanic, population
* `NH_AMIN`: American Indian and Alaska Native, non-hispanic, population
* `NH_ASIAN`: Asian, non-hispanic, population
* `NH_NHPI`: Native Hawaiian and Pacific Islander, non-hispanic, population
* `NH_OTHER`: Other race, non-hispanic, population
* `NH_2MORE`: Two or more races, non-hispanic, population
* `HISP`: Hispanic population
* `H_WHITE`: White, hispanic, population
* `H_BLACK`: Black, hispanic, population
* `H_AMIN`: American Indian and Alaska Native, hispanic, population
* `H_ASIAN`: Asian, hispanic, population
* `H_NHPI`: Native Hawaiian and Pacific Islander, hispanic, population
* `H_OTHER`: Other race, hispanic, population
* `H_2MORE`: Two or more races, hispanic, population
* `VAP`: Total voting age population
* `HVAP`: Hispanic voting age population
* `WVAP`: White, non-hispanic, voting age population
* `BVAP`: Black, non-hispanic, voting age population
* `AMINVAP`: American Indian and Alaska Native, non-hispanic, voting age population
* `ASIANVAP`: Asian, non-hispanic, voting age population
* `NHPIVAP`: Native Hawaiian and Pacific Islander, non-hispanic, voting age population
* `OTHERVAP`: Other race, non-hispanic, voting age population
* `2MOREVAP`: Two or more races, non-hispanic, voting age population
* `CD_12`: 2012 enacted congressional district ID
* `CD_16`: 2016 enacted congressional district ID
* `HDIST_11`: 2011 enacted House of Delegates district ID
* `HDIST_REM`: 2019 remedial House of Delegates district ID
* `SENDIST`: 2011 enacted state senate district ID

## Projection
This shapefile uses a NAD83/Virginia Lambert projection or EPSG: 3968.