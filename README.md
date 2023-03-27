
# Python: Seaborn - Car Market Analysis

After completing the course I have gained new skills and knowledge that will enable me to explore the power of Seaborn for data visualization and analysis in a well-organized, documented, and easy-to-understand way.

In addition, I am excited to showcase my newfound skills by sharing a mini project, which will demonstrate my ability to use Seaborn to analyze and visualize data effectively.


## Authors

- [@KuchP](https://github.com/KuchP)


## Documentation

 - Data set:

### Car Market Analysis:

Collecting data between 1982 and 2015 from market in USA.

Data set contain: \
'year'\
'make'\
'model'\
'trim'\
'body'\
'transmission'\
'vin'\
'state'\
'condition'\
'odometer'\
'color'\
'interior'\
'seller'\
'mmr'\
'sellingprice'\
'saledate'\
'condition_bin'\



### Data Analysis points:

Problem statement: Looking at general overview about Data Set to find more insights and to find famous model with potential best opportunity to buy new car.

### Data pre-processing:
Change dtypes in 'category' to make decrease memory.\
Cleaning data from type latter to have data more value.\
Finding NA and checking is the missing data have impact for sellingprice.

### Data analysis methodology:
I was using:\
Pandas\
Seaborn\
Scipy.stats

### Results and findings

1. Most missing data was founded in column 'Transmission' and The absence of missing values in the transmission variable did not have a substantial impact on the selling price of the vehicles in the dataset.

2. During analyzing top5 selling brand i found that The negative correlation coefficient values indicate that as the odometer reading increases, the selling price decreases for all the car brands. This is a common trend in the used car market, as higher mileage is generally associated with greater wear and tear on the vehicle.\

* Toyota was the brand which sellingprice drop slowest comparing to rest top_5 selling brands\

* Ford in other hand have the fastes drop selling price comparing to odometer.

3. Analyzing the SellingPrice vs odometer for top 5 selling prices brands.


* Bentley has the strongest negative correlation coefficient, indicating that there is a stronger relationship between odometer and selling price for Bentley cars compared to the other brands. On the other hand, Acura has the slowest regression in top5 brands.

4. Based on my findings, BMWs exhibit the strongest correlation between their selling price and condition.

5. It appears that the F-150 model is the most popular in the USA, particularly the (XLT, XL) 'trim' have relatively low prices. After researching the best place to buy an XLT F-150, I found that Utah offers the best value compared to other locations, making it a potentially ideal place to purchase the vehicle at a lower price.





