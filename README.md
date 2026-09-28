[![R](https://img.shields.io/badge/R-RMarkdown-276DC3?logo=r&logoColor=white)](https://rmarkdown.rstudio.com/)

# Statistical Computing in R

Four assignments and ten labs from an intro statistics course, done entirely in R
Markdown — sampling design, data wrangling, hypothesis testing, and regression, each
`.Rmd` mixing write-up with executable R (mostly `dplyr`/`ggplot2`) against a real
dataset.

## Assignments

| # | Dataset | Topic |
|---|---------|-------|
| [`assignments/assignment-1/`](assignments/assignment-1/) | `casino.csv` | Sampling and experimental design — population vs. sample, convenience vs. simple random sampling. |
| [`assignments/assignment-2/`](assignments/assignment-2/) | `Government_expenditure_per_student.csv`, `Superstores.csv`, `rawgrades.csv` | Data wrangling and summary statistics across three separate datasets. |
| [`assignments/assignment-3/`](assignments/assignment-3/) | `homework3Data.csv` | Statistical inference. |
| [`assignments/assignment-4/`](assignments/assignment-4/) | `AdmissionPredict.csv` | Regression — predicting graduate admission chances. |

## Labs

| # | Dataset | Topic |
|---|---------|-------|
| [`labs/lab-01/`](labs/lab-01/) | — | Written worksheet (no R component). |
| [`labs/lab-02/`](labs/lab-02/) | `FlowerData.csv` | Intro data exploration. |
| [`labs/lab-03/`](labs/lab-03/) | `inflation_consumer.csv` | Data wrangling. |
| [`labs/lab-04/`](labs/lab-04/) | — | R fundamentals. |
| [`labs/lab-05/`](labs/lab-05/) | `data_wk5.csv` | Sampling distributions. |
| [`labs/lab-06/`](labs/lab-06/) | `grades.csv` | Summary statistics. |
| [`labs/lab-07/`](labs/lab-07/) | `lab7_data.csv` | Hypothesis testing. |
| [`labs/lab-08/`](labs/lab-08/) | `RealEstate.csv` | Regression basics. |
| [`labs/lab-09/`](labs/lab-09/) | `media_spend.csv` | Bootstrapping / resampling. |
| [`labs/lab-10/`](labs/lab-10/) | `media_spend.csv` | Further regression / model diagnostics. |

## Running

Open any `.Rmd` in RStudio and Knit, or from the command line:

```r
rmarkdown::render("assignments/assignment-1/assignment1.Rmd")
```

Each file expects its CSV(s) in the same directory (already colocated per folder above).

## 🎓 Project Context

Built as part of **STAT 123: Applied Statistics for Computer Science** at the
University of Victoria.

## ⚠️ Academic Integrity Notice

This repository is maintained for portfolio and educational purposes only. If you are
currently enrolled in STAT 123 at the University of Victoria or a similar applied
statistics course, please note that using this code in your own assignments may
constitute a violation of Academic Integrity policies.
