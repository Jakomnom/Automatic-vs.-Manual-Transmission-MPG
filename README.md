# Motor Trend Analysis: Automatic vs. Manual Transmission MPG

This repository contains the code and analysis for exploring the relationship between transmission type (automatic vs. manual) and miles per gallon (MPG) using the `mtcars` dataset. The analysis was conducted as part of a project for Motor Trend magazine.

---

## Project Overview

The goal of this project is to answer the following questions:

1. **Is an automatic or manual transmission better for MPG?**  
2. **Quantify the MPG difference between automatic and manual transmissions.**  

The analysis includes:  
- Exploratory Data Analysis (EDA)  
- Regression modeling  
- Model diagnostics  
- Quantification of uncertainty using confidence intervals  

---

## Dataset

The analysis uses the `mtcars` dataset, which is included in R. This dataset contains information about 32 cars, including:

- `mpg`: Miles per gallon  
- `am`: Transmission type (0 = automatic, 1 = manual)  
- `wt`: Weight (in 1000 lbs)  
- `hp`: Horsepower  
- Other variables related to car performance and design  

For more details about the dataset, see the [R documentation](https://www.rdocumentation.org/packages/datasets/versions/3.6.2/topics/mtcars).

---

## Repository Structure
```
Motor-Trend-Analysis/ 
├── README.md # This file
├── analysis.Rmd # R Markdown file for the analysis 
├── analysis.pdf # Compiled PDF report 
└── analysis.html
```

---

## How to Use This Repository

1. **Open the R Markdown file**:
   - Open `analysis.Rmd` in RStudio.
   - Install any required packages (e.g., `ggplot2`).

2. **Run the analysis**:
   - Knit the `analysis.Rmd` file to generate the PDF report (`analysis.pdf`).

3. **View the results**:
   - The compiled PDF report contains the full analysis, including exploratory data analysis, regression modeling, and conclusions.
  
4. **View the results**:
   - The compiled PDF report contains the full analysis, including exploratory data analysis, regression modeling, and conclusions.

## Key Findings

- **Manual transmissions are associated with higher MPG** compared to automatic transmissions.
- After adjusting for weight and horsepower, the MPG difference between manual and automatic transmissions is approximately **2.9 MPG**.
- The 95% confidence interval for this difference is **1.5 to 4.3 MPG**.

---

## Dependencies

The analysis requires the following R packages:
- `ggplot2` (for data visualization)
- `knitr` (for compiling the R Markdown document)

You can install these packages using:
```r
install.packages(c("ggplot2", "knitr"))
```
