## EDA soft construct
In this project was considered open source dataset from Google Big Query 'iowa liquor sales'.
This dataset contains the spirits purchase information of Iowa Class “E” liquor licensees by product and date of purchase from January 1, 2012 to current. The dataset can be used to analyze total spirits sales in Iowa of individual products at the store level.
All descriptions of features, data srtucture and insights were looking on **EDA.ipynb** file .
Before downloading project be sure that your Python version is equal or greater than 3.6 and 64bit 
Follow instructions below:

 - clone it
 - setup next libraries by pip (jupyter notebook, pandas, pandas-gbq, scipy, numpy, matplotlib )
 - Run the **EDA.ipynb** on Jupyter Notebook.
Also you can open EDA.ipynb in github, but styling will not working on web version
**Warning: there are two places in code, which executes near hour. It was done for investigating general distributions.
In real working, it is desirable to avoid such none-optimized queries. But I wanted to make full analysis.**
