# Disparate Impacts of College Admissions Policies

Replication materials for [The Disparate Impacts of College Admissions Policies on Asian American Applicants](https://www.nber.org/papers/w31527) (2023) by Joshua Grossman, Sabina Tomkins, Lindsay Page, and Sharad Goel.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/joshuagrossman/asian-admission-di/blob/main/replication.ipynb)

We provide anonymized and aggregated data to replicate the main findings of the paper. All of the data released here appear in Tables 16-21 in the appendix of the paper.

### Data description
`data/race_zip1_act_legacy.csv`: Number of white and Asian American applicants and admitted students, disaggregated by race, first digit of the high school ZIP code, ACT-equivalent test score, and legacy status.

`data/ethnicity_zip1_act_legacy.csv`: Number of white and Asian American applicants and admitted students, disaggregated by Asian subgroup, first digit of the high school ZIP code, ACT-equivalent test score, and legacy status.

`data/race_act_legacy.csv`: Number of white and Asian American applicants and admitted students, disaggregated by race, ACT-equivalent test score, and legacy status.

`data/ethnicity_act_legacy.csv`: Number of white and Asian American applicants and admitted students, disaggregated by Asian subgroup, ACT-equivalent test score, and legacy status.

In all cases, the number of admitted students is estimated based on the enrollment proxy described in the paper. To preserve anonymity, we only include cells with at least 50 applicants and one admitted student. 

### Code

The [replication code](https://colab.research.google.com/github/joshuagrossman/asian-admission-di/blob/master/replication.ipynb) uses the default `R` runtime on Google Colab. 
No local software installation is required, nor does any data need to be downloaded. 
The replication code should finish running in less than one minute. 
