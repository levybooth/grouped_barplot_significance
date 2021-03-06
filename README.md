# grouped_barplot_significance

Version 0.01

By: David Levy-Booth, 04/10/2016

Function for R to produce a grouped barplot using ggplot2 showing 1-way ANOVA significance levels between all treatments (using letters) and between grouping factors (using stars). 

#USAGE: 

Download script and link as source in R script: 

```python
source("barplot_sig.R")

y_plot <- soil_barplot(y ~ X1 + X2 + X3, data, "title")
```

Where: 

y is the y variable that appears on the y axis, 

X1 is the treatment variable 

X2 is the first grouping variable upon which the treatments will be paired in the plot

X3 is the second grouping variable that will be differentiated by color

The output is a standard ggplot2 object, that can saved or be further modified by additional ggplot2 compatable instructions. 


#OUTPUT: 
![DOC concentrations](img/DOC_barplot.png)

DOC concentrations between treatments 
