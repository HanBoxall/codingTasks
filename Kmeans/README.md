[Country-data.csv](https://github.com/user-attachments/files/15570954/Country-data.csv)# coding Tasks for CoGrammar Data Science Bootcamp

Here is an example of one of the tasks I completed as part of the Data Science Bootcamp

## Unsupervised Learning - K-Means Clustering

The objective of the task was to group countries using socio-economic and health factors to determine the development status of the country using K-means clustering.

### Prerequisites

The dataset used was the csv file in this repository ![Country-data](Kmeans/Country-data.csv)

Required installs for this task:
- numpy
- pandas
- matplotlib.pyplot
- seaborn
- sklearn

## Running the tests

After preprocessing, I explored the data using scatterplots to visualise what variables may be categorised into clusters. I then scaled the data to make the model perform better. An elbow curve and silhouette score was calculated to decide how many clusters K was optimum. A K-means model was then fitted, and the silhouette score 0.52 indicated that it was a reasonably good model.
![kmeans](https://github.com/HanBoxall/codingTasks/assets/164758748/afc80739-cdcb-4f9d-b58a-1e1c7abd8cfa)
![silhouette](https://github.com/HanBoxall/codingTasks/assets/164758748/75aa0e68-695b-4ab3-ad01-f2bae24861a7)


### Output

![childmort_vs_GDPP](https://github.com/HanBoxall/codingTasks/assets/164758748/1fb8572c-236a-438c-bacf-6b4fb5a7bbc9)

From this graph I defined Cluster 0 as 'Developing', Cluster 1 as 'Developed' and Cluster 2 as 'Least Developed'. The 'Least Developed' countries have the highest child mortality and lowest GDP per Capita. The 'Developed' countries have the lowest child mortality and highest GDP per Capita.
