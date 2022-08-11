# Used Cars Data Exploration

## by Adeoje Olabisi


## Dataset

The dataset is madeup of 7906 rows and 18 columns in general. Based on various market surveys, the consulting firm has gathered a large dataset of different types of used cars across the market. The dataset is madeup of different information about used cars gotten from [kaggle.](https://www.kaggle.com/datasets/shubham1kumar/usedcar-data?resource=download). The description of data can be gotten from [here](https://www.kaggle.com/datasets/shubham1kumar/usedcar-data?resource=download).


## Summary of Findings

I've seen that the two major variables that affect the selling price of cars in the dataset are max_power and km_driven. I also saw the time trends of sales across the regions, where it was observed that some of the regions do not have sale in some years.

In a bit to explore the data, I carried out univariate visualization which allow me to see into the distribution of various variables in the dataset across its levels. I also carried out bivariate visualization which shows the relationship between variables while multivariate visualization is used to show the effect of some variables on the relationships in bivariate visualization. The exploration has help to see the strong correlation between max_power and engine variables.


## Key Insights for Presentation

I will just focus on the effect of max_power and km_driven on the selling price of used cars in the dataset. Also, I will be looking into time trends of sale across regions and features of sold cars. 

I look at the distribution of selling price, of maximum power and that of total distance travelled by cars in the dataset. In a bit to look at the distribution of selling price across the data set, the histogram shows that cars whose selling price is between $30,000 and $1,000,000 are much in the dataset. But in order to dive deeper into the dataset, log transformation was carried out on the price axis, this later shows that the price distribution is a unimodal distribution in which the modal price is in between $300,000 and $400,000. After $1,000,000, it was oberved that the price is rising and falling in the counts.

It was observed that there is a negative correlation between the selling price and km_driven. This implies that an increase in the value of  km_driven will lead to a decrease in the selling price. The scatterplot of max_power against selling price shows that there is a strong relationship between the selling price of a car and the max_power of the car i.e. as the max_power of cars increases, the selling price also increase and vice versa.

I also observe the acceptance of seller types across the regions based on sales. The chart shows that the Dealer seller type has the highest popularity across the region based on the total sales.

The trends of price across the year shows that the price of cars is increasing over the years, except in 2001, 2006, 2012, 2014 and 2018 where there is a slight fall in the price, then a great hike in price from 2018 to 2019 wih great fall in the following year 2020. The disjoint in 1995 to 1999 simply shows that there is no sales in those years.