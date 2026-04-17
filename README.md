# Network Analysis of Statistical Anxiety

This project applies network analysis to study the structure of statistical anxiety using the Statistics Anxiety Rating Scale (STARS). It compares factor-based and network-based approaches and explores intervention targets using key player analysis.

## Goals

- Examine the structure of statistical anxiety  
- Compare factor and network approaches  
- Identify central components in the network  
- Evaluate intervention targets using key player analysis  

## How to Use

### Step 1: Download the repository

1. Click the green **Code** button on GitHub  
2. Select **Download ZIP**  
3. Unzip the folder  

### Step 2: Run the analysis

1. Open `finalanalysis.Rmd` in RStudio  

2. Install required packages:

```r
install.packages(c("bootnet", "tidyverse", "igraph", "networktools", "keyplayer"))
```

## Key Files

- `finalanalysis.Rmd` — main analysis script  
- `finalanalysis.html` — rendered report  
- `stars-data_132.csv` — dataset  


## RData Objects

The following files are included to reduce computation time:

- `boot_strength.RData`  
- `kpresults.RData`  
- `stars_kp_boot.RData`  
