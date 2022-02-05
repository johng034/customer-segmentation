# Summary
In this project, we will work with a dataset containing data gathered from customers, such as their education level, income, purchases, number of visits to the company’s website, etc. The link to the original dataset can be found [here](https://www.kaggle.com/imakash3011/customer-personality-analysis).

## Goal
__The goal of this project is to group customers that share similar purchasing patterns to better understand our customers.__

This information is helpful because we could use strategies such as targeted advertising to personalize our message to each group. We could also identify kinds of customers that we may have not known about earlier. 

# Model
For this project, we used the **k-means clustering algorithm**. We decided on grouping the data into *four* clusters based on the inertia and silhouette scores for each number of clusters ranging from 2 to 12.

In the `Modeling` iPython notebook, we saved the final dataset with the labels included. This dataset can be explored further using spreadsheets, visualization software, or Python/R.

# Update
While I was exploring the dataset with Tableau, I realized that groups 1 and 2 seemed quite similar and clusters 0 and 3 were also similar. The only difference between those two subgroups was that one group had children while the other group did not. I believe this is because the Boolean values (`0` and `1`) in the `Has_child` column have a significant effect on the algorithm, therefore also affecting the output.

When I went back to correct the error, I thought about the [CRISP-DM](https://en.wikipedia.org/wiki/Cross-industry_standard_process_for_data_mining) framework and re-evaluated the columns I should analyze.

<br>

![image](https://www.researchgate.net/profile/Vernon-Dsouza/publication/326235288/figure/fig1/AS:645518493495296@1530915010595/CRISP-DM-Model-Taylor-2017.png)

When I was in the Evaluation stage, I went back to the Business Understanding and Data Understanding phases to explore different columns that may be more useful for our goal.

I'm currently working on analyzing clusters using different columns.
