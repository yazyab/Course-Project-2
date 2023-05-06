# Course-Project-2
Course Project-2
Assignment
The overall goal of this assignment is to explore the National Emissions Inventory database and see what it say about fine particulate matter pollution in the United states over the 10-year period 1999–2008. You may use any R package you want to support your analysis.

You must address the following questions and tasks in your exploratory analysis. For each question/task you will need to make a single plot. Unless specified, you can use any plotting system in R to make your plot.

Question 1
Have total emissions from PM2.5 decreased in the United States from 1999 to 2008? Using the base plotting system, make a plot showing the total PM2.5 emission from all sources for each of the years 1999, 2002, 2005, and 2008.

Answer 1
Total emissions from PM2.5 have decreased in the US from 1999 to 2008 by 3.868760910^{6} tons, as illustrated in the plot 1.png

Question 2
Have total emissions from PM2.5 decreased in the Baltimore City, Maryland (𝚏𝚒𝚙𝚜 == “𝟸𝟺𝟻𝟷𝟶”) from 1999 to 2008? Use the base plotting system to make a plot answering this question.
Answer 2
Total emissions from PM2.5 in Balitmore have decreased from 1999 to 2008 by 1411.8984892 tons, as demonstrated in the plot 2.png
Question 3
Of the four types of sources indicated by the 𝚝𝚢𝚙𝚎 (point, nonpoint, onroad, nonroad) variable, which of these four sources have seen decreases in emissions from 1999–2008 for Baltimore City?

Which have seen increases in emissions from 1999–2008? Use the ggplot2 plotting system to make a plot answer this question.
Answer 3
All source types appear to have decreased from 1999 to 2008 in Baltimore, with the exception of of the “point” type source.
Question 4
Across the United States, how have emissions from coal combustion-related sources changed from 1999–2008?

Answer 4
Total coal combustion emissions in the US have decreased by 2.286942810^{5} tons from 1999 to 2008.
Question 5
How have emissions from motor vehicle sources changed from 1999–2008 in Baltimore City?
Answer 5
Emissions from motor vehicles in Baltimore have decreased by 258.5445426 tons from 1999 to 2008.

Question 6
Compare emissions from motor vehicle sources in Baltimore City with emissions from motor vehicle sources in Los Angeles County, California (𝚏𝚒𝚙𝚜 == “𝟶𝟼𝟶𝟹𝟽”). Which city has seen greater changes over time in motor vehicle emissions?
Answer 6
The greatest magnitude of change in motor vehicle emissions occurred in Baltimore City which experienced a decrease of 258.5445426 tons, while Los Angeles experienced an increase of 163.43998 tons during the 1999-2008 period.
