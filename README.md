# Supply_Chain_EDA
## Goal
In order to enhance the user logistics service experience, the supply chain cooperates to prepare the goods in advance in the local warehouses, reducing the logistics timelines, improving the user logistics service experience, procurement of goods and transportation, etc. Under the background of the rapid development of big data and using big data analysis provide data foundation for the supply chain to improve their processes.
## Exploratory Data Analysis
- This dataset is about Supply Chain of any retail store. It consists of 8 csv files. The size of dataset is over 2GB. All files have shapes, so I didn't concat or join them.
- Mainly upload all files and convert their date columns into proper datetime format.
- Because of Big Data, I choose the sample of datssets for data analysis.
## Comparision Between Dask vs Pandas
- It is found that 15 ms took pandas to read and 12 ms took dask to read fulldate csv file. Dask is faster than pandas becasue of parallel computing.
## Promotion Goods
### Findings
- There are many similar goods. All similar goods have same products_ID but all goods have unique sku_ID. 
- The main colums of the data sets are data_date (representing date), good_price, orignal shop price and promotion price.
- Add Percentage_Discount Column: It shows the discount percentage of each good
- Top 10 frequently goods on promotion are visualized

## Goods Sale
- Shows sales of goods
- Which goods have high demand?
- Retrive Monthly Sales and visualized
### High Demanding Goods
- High demanding goods are displayed

## Daily Sale of Goods
- It shows day-day data. Means how many times in a day a specific good sale, how many times user click on that goods, add in the cart and include in the favourites.
- It has more than 1GB data with 35201588 rows.
- Relation between goods-click and goods-sale visualized via scartted plot.

# Conclusion
- We can also see 195,498 kinds of goods sold but in dataset it is mentioned above 423453 goods. It means still lot of goods in the store which never sale.
- Never sale goods should go on high promotion with maximum discount offer
- High demanding goods needs to be present at the store.

# Visualization
I used
  - Matplotlib
  - Plotly



