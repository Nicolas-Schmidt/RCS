
<!-- README.md is generated from README.Rmd. Please edit that file -->

## roll-call and speech

**Diego Luján, Nicolás Schmidt and Juan Andrés Moraes**

This repository contains the article data: *Estimating parties’ policy
positions in Uruguay: comparing scaling methods based on legislative
speeches and roll-call votes*. Additionally, in this repository you will
find the replication files and additional material.

- [Data](https://github.com/Nicolas-Schmidt/rollcall-speech)
- [R code](https://github.com/Nicolas-Schmidt/rollcall-speech)

### Data speechuy

The parliamentary speeches database contains the following variables:

| Variable    | Description                                |
|-------------|--------------------------------------------|
| legislature | legislature number                         |
| chamber     | chamber                                    |
| legislator  | name of the legislator                     |
| party       | legislator’s party                         |
| date        | Date of the session                        |
| id          | floor speech identifier                    |
| speech      | legislator’s speech                        |
| sex         | sex                                        |
| district    | for the lower house the electoral district |

##### Descriptive statistics of legislative speeches in Uruguayan parliament 1985-2015

| Legislature | Legislattors | session | speech | word average |
|-------------|--------------|---------|--------|--------------|
| 1985-1990   | 236          | 424     | 7645   | 1156         |
| 1990-1995   | 243          | 433     | 7035   | 1012         |
| 1995-2000   | 190          | 381     | 4878   | 1211         |
| 2000-2005   | 316          | 685     | 13137  | 988          |
| 2005-2010   | 326          | 665     | 12952  | 987          |
| 2010-2015   | 284          | 684     | 11648  | 1232         |

##### Number of words contained in individual legislator’s speeches in Uruguayan Parliament 1985-2015, by party

<img src="figures/eda.png" style="margin-center:30px;margin-bottom:5px;" width="800" align="center"></a>

<!-- badges: start -->
<!-- badges: end -->
