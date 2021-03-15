# biostat629
## Getting Started

### Prerequisites

Things you need to install beforehand so that this script can run smoothly

```
install.packages("dplyr")
install.packages("data.table")
install.packages("gtsummary")
install.packages("mice")
install.packages("geepack")
install.packages("stats")
install.packages("forestplot")
```

### Usage
There are six trunks of codes:
* Data read-in on the cluster (This chunk needs to be run on the server: armis2.arc-ts.umich.edu; slurm scripts are under my home directory)
* Date exploration and combination 
* Multiple imputation using MICE
* Logistic regression analysis
* Output visualization
* Model diagnostics

