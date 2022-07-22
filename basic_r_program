#multiply numbers
31*78

#divide nubers
697/42

#add numbers
314+654

#subtract numbers
56765-23

#assign values to variables
x <- 39
y <- 14
z <- x+y
a <- sqrt(2345)
log2(a)

#create vectors
vec1 <- c(2,5,8,12,16)

#generate sequence of numbers
vec2 <- c(seq(2, 300, 3))

#Extract values at specified positions or a range of positions (indexing)
vec2[5]
vec2[10]
vec2[15]
vec2[20]
vec2[10:30]

#create dataframe
mouse_colour <- c('purple','red','yellow','brown')
mouse_weight <- c(23, 21, 18, 16)
mouse_info <- data.frame('colour'=mouse_colour, 'weight'=mouse_weight)
View(mouse_info)

#import data set from internet
small_file <- read.table('https://raw.githubusercontent.com/HackBio-Internship/public_datasets/main/R/small_file.txt')
View(small_file)
child_variant <- read.csv('https://github.com/HackBio-Internship/public_datasets/blob/main/R/Child_Variants.csv?raw=true')
head(child_variant)

#perform functions on data frame
#calculate mean of column
mean(child_variant$MutantReadPercent)

#filter column
child_variant[child_variant$MutantReadPercent >= 70,]

#alternatively use
install.packages('dplyr')
library(dplyr)
filter(child_variant, MutantReadPercent >= 70)

#import irish flower dataset
irish_flower <- read.csv('https://gist.github.com/curran/a08a1080b88344b0c8a7/raw/0e7a9b0a5d22642a06d3d5b9bcbad9890c8ee534/iris.csv')

#ggplot grouped bar chart
#loading appropriate libraries
install.packages('ggplot2')
library(ggplot2)
library(reshape2)

#barplot
irish_barplot <- ggplot(data=irish_flow, aes(x=species, y=value, fill=variable))
irish_barplot + geom_bar(stat="identity", position="dodge") 
