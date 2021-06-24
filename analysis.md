The distribution of the stars according to country was done in R version 4.0.3 (2020-10-10)

The following commands were used
```
data <- read.csv("ramen-ratings.csv",header=T) # reading in data
plot1 <- table(data$Stars,data$Country)# subsetting data
plot <- barplot(plot1, main= "stars distribution") #construction of the barplot
saveRDS(plot,"plot1.png") #saving the plot
```
