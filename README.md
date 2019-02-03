## Basic scatter plot: y ~ x
xyplot(y ~ x, data)
#Default plot
xyplot(Sepal.Length ~ Petal.Length, data = my_data)

# Color by groups
xyplot(Sepal.Length ~ Petal.Length, group = Species, 
       data = my_data, auto.key = TRUE)
