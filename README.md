### Exploratory data analysis of Airbnb Seattle dataset
#### Dependencies
To run the notebook, the following python packages are required:<br />
   &nbsp;&nbsp;&nbsp; numpy <br />
   &nbsp;&nbsp;&nbsp;     matplotlib <br />
   &nbsp;&nbsp;&nbsp;     pandas <br />
   &nbsp;&nbsp;&nbsp;    folium <br />
   &nbsp;&nbsp;&nbsp;     sklearn <br />
This notebook goes through data preparation, preparation and visualizaitons to answer the following questions: <br />
The dataset can be downloaded from [here](https://www.kaggle.com/airbnb/seattle/data)

##### &nbsp;&nbsp;&nbsp; 1. How the listing prices are distributed?
##### &nbsp;&nbsp;&nbsp; 2. Which months are priciest ?
##### &nbsp;&nbsp;&nbsp; 3. Which months are the busiest to visit Seattle? Does busy month also means expensive?
##### &nbsp;&nbsp;&nbsp; 4. What is the distribution of the listings in the city borders? are they evenly distribued or concentrated in few neighbourhoods?
##### &nbsp;&nbsp;&nbsp; 5. What can be said aboud the vibe of the neighbourhoods based on reviews?
In the notebook, the questions are analysed step-by-step to arrive at data-driven conclusions.
To render some plots (maps) on the notebook, you can use [nbviewer](http://nbviewer.org/). 
### Summary of Findings:
1. The mass of weekly price listings is in the range of $100 - $1000 but the distribution has a long right tail (maximum upto $6300) <br />
2. On average, July is the most expensive month followed closely by August and June. <br />
![alt text](price_barplot.PNG "Barplot of average monthly prices")

3. Based on the amount of reviews received, it seems that Seattle is visited most in August. <br />
4. Most of the listings are concetrated in just few neighbourhoods of Seattle (e.g. Broadway, Belltown ...). <br />
5. Based on the frequent words appearing in reviews/comments, some information about the feel/vibe of each neighbourhood can be infered. <br />

![alt text](heatmap.PNG "Heatmap of Airbnb listings")

### Acknowledgement
&nbsp;&nbsp; [1]. Inside Airbnb initiative, link [here](http://insideairbnb.com/about.html). <br />
&nbsp;&nbsp; [2]. Visualization of text data (a blog post from towards data science), link [here](https://towardsdatascience.com/a-complete-exploratory-data-analysis-and-visualization-for-text-data-29fb1b96fb6a). <br />
### Medium blog post summarizing the results is available [here](https://medium.com/@daazene/airbnb-seattle-dataset-basic-exploratory-data-analysis-b2615b2a44ef). 
