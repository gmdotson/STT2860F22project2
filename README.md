# Instructions

* Fork this repository into your own GitHub account
* Clone the repository to your RStudio server account

You will use the three datasets below in your project. They are included in the GitHub repository. All data was sourced from [Death Penalty Information Center](https://deathpenaltyinfo.org/).

***
`cappunish.rds` : Selected data about the death penalty in the United States as of November 6, 2022. 

### Variables

* `state`: state name (including District of Columbia)
* `region`: US Census region
* `division`: US Census regional subdivision
* `court`: US Court of Appeals regional circuit 
* `dp1`: whether or not the state legally has the death penalty (yes/no)
* `dp2`: `dp1` but also indicates states that have a governor's moratorium
* `abolished`: year capital punishment was legally abolished in the state
* `post1976`: number of executions after 1976 (state only)
* `pre1976`: number of executions before 1976 (may include federal/military)
* `prisoners`: total number of prisoners currently on death row
* `women`: number of women on death row (subset of `prisoners`)
* `freed`: number of innocent people later freed from death row
* `clemency`: number of people who were granted clemency
* `felony`: whether someone can get the death penalty as a felony accessory
* `sentence`: who decides on whether someone gets a death penalty sentence

***

`deathrowsize.rds` : Number of prisoners on death row in the U.S. for each year from 1968 to 2021.

### Variables

* `year`: year
* `total`: total prisoners on death row

***

`deathsentencesNC.rds` : Number of people given death sentences per year in N.C. for each year from 1977 to 2021.

### Variables

* `year`: year
* `total`: total number of sentences
