# Summary
In this project, we will work with a dataset containing data gathered from customers, such as their education level, income, purchases, number of visits to the company’s website, etc. The link to the original dataset can be found [here](https://www.kaggle.com/imakash3011/customer-personality-analysis).

# Data Visualization
We created a Tableau dashboard for the number of products purchased, where customers made purchases, and the success of past campaigns. You can find our [Tableau Dashboard here](https://public.tableau.com/views/CustomerAnalysis_16517054386160/PurchasesDashboard?:language=en-US&:display_count=n&:origin=viz_share_link).

<div class='tableauPlaceholder' id='viz1651792103027' style='position: relative'><noscript><a href='https://public.tableau.com/views/CustomerAnalysis_16517054386160/PurchasesDashboard?:language=en-US&:display_count=n&:origin=viz_share_link'><img alt='Purchase Overview ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Cu&#47;CustomerAnalysis_16517054386160&#47;PurchasesDashboard&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='CustomerAnalysis_16517054386160&#47;PurchasesDashboard' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Cu&#47;CustomerAnalysis_16517054386160&#47;PurchasesDashboard&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>

# Goal
__The goal of this project is to group customers that share similar purchasing patterns to better understand our customers.__

This information is helpful because we could use strategies such as targeted advertising to personalize our message to each group. We could also identify groups of customers that we may have not known about earlier. 

# Model
For this project, we used the **k-means clustering algorithm**. We decided on grouping the data into *five* clusters based on the inertia and silhouette scores for each number of clusters ranging from 2 to 12.

In the `Modeling` iPython notebook, we saved the final dataset with the labels included. This dataset can be explored further using spreadsheets, visualization software, or Python/R.

