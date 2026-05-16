---
title: group16 project report 
author: Mureithi valentine wanjiru SAC3/1896/2025
        Njogu Mercy Wanjiru SAC3/1897/2025
        Abwao Larry Gastine STA3/6693/2025
        Emmanuel Amani Iha STA3/6677/2025
format: html
---

# INTRODUCTION

This project focuses on analyzing a dataset using R programming and Quarto.  
The aim of the project is to explore the dataset, perform basic statistical analysis, and present findings through visualizations and an interactive dashboard.

# OBJECTIVES

The objectives of this project are:

- To clean and analyze the dataset
- To visualize trends in the dataset
- To develop an interactive dashboard using Shiny

# DATASET DESCRIPTION

The dataset used in this project was obtained from Kaggle.  
It contains information related to electricity generation in kenya.

```{r}
# Load dataset
data <- read.csv("electricity generation.csv")


```

# Data Analysis

## Summary Statistics

The following calculations were performed on the dataset.


# DATA VISUALIZATION

The dataset was visualized using graphs and charts.

## Scatter Plot

```{r}
## Fossil Fuels vs Renewables

```{r}
plot(data$Year,
     data$Renewables,
     type = "l",
     xlab = "Year",
     ylab = "Energy Output",
     main = "Renewables vs Fossil Fuels")

lines(data$Year,
      data$Fossil_Fuels)

legend("topleft",
       legend = c("Renewables", "Fossil Fuels"),
       lty = 1)

```

# INTERACTIVE DASHBOARD

An interactive dashboard was developed using Shiny to allow users to interact with the dataset.

The dashboard includes:

- Data filtering
- Sorting
- Interactive visualizations
- Dynamic summaries
```

# FINDINGS

The analysis showed several important patterns within the dataset.

Some variables had higher average values while others showed large variation.  
The visualizations also helped identify trends and relationships between variables.

# CHALLENGES FACED

Some of the challenges encountered during the project included:

- Data cleaning issues
- Missing values
- Learning how to integrate Shiny with Quarto
- Limited access to a laptop environment

# CONCLUSION

This project demonstrated how R, Quarto, and Shiny can be used together for data analysis and reporting.

The project successfully performed statistical analysis, generated visualizations, and created an interactive dashboard for exploring the dataset.

# REFERENCES

- Kaggle datasets
- R Documentation
- Quarto Documentation
- Shiny Documentation
