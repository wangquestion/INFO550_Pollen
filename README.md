# INFO550_Pollen

For this project, I will analyze the pollen sensor data.

To git a time series plot for the site, you will need several `R` pacakages: ggplot2, stringr, dplyr

install those pacakges:
```{r}
install.packages(c('ggplot2','stringr','dplyr'))
```

# Execute the RMD code

To execute the code, under the repo you ca run

```
Rscript -e "rmarkdown::render('INFO550_HW2_WWang.Rmd')
```

This will create a file named `INFO550_HW2_WWang.html` in your directoriy that contains the plot.
