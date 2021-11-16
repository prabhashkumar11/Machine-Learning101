## Trends - A trend is defined as a pattern of change.
 ```
 1.sns.lineplot - Line charts are best to show trends over a period of time, and multiple lines can be used to show trends in more than one group.
 ```
## Relationship - There are many different chart types that you can use to understand relationships between variables in your data.
```
 1.sns.barplot - Bar charts are useful for comparing quantities corresponding to different groups.
 2.sns.heatmap - Heatmaps can be used to find color-coded patterns in tables of numbers.
 3.sns.scatterplot - Scatter plots show the relationship between two continuous variables; if color-coded, we can also show the relationship with a third categorical variable.
 4.sns.regplot - Including a regression line in the scatter plot makes it easier to see any linear relationship between two variables.
 5.sns.lmplot - This command is useful for drawing multiple regression lines, if the scatter plot contains multiple, color-coded groups.
 6.sns.swarmplot - Categorical scatter plots show the relationship between a continuous variable and a categorical variable.
 ```
## Distribution - We visualize distributions to show the possible values that we can expect to see in a variable, along with how likely they are.
```
 a.sns.distplot - Histograms show the distribution of a single numerical variable.
 b.sns.kdeplot - KDE plots (or 2D KDE plots) show an estimated, smooth distribution of a single numerical variable (or two numerical variables).
c.sns.jointplot - This command is useful for simultaneously displaying a 2D KDE plot with the corresponding KDE plots for each individual variable.
```
**Seaborn has five different themes: (1)"darkgrid", (2)"whitegrid", (3)"dark", (4)"white", and (5)"ticks", 
and you need only use a command similar to the one in the code cell above (with the chosen theme filled in) to change it.**
