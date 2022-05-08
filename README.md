# ds-assignment
I've used LightFM to make recommendations as it is very flexible to use(It gives the flexibility of giving data directly to the recommendation system).

For recommendation problem, there is not very good matrics for evaluating. But luckily lightfm provides us a very rich set of evaluating matrics like AUC, Precision at K, Recall at K, Reciprocal Rank.

For making predition I've used jaccard metric as Jaccard similarity index (sometimes called the Jaccard similarity coefficient) compares members for two sets to see which members are shared and which are distinct It’s a measure of similarity for the two sets of data, with a range from 0% to 100%. The higher the percentage, the more similar the two populations. We have find Jaccard metric for

1.Predicted vs Actual pratilipi Id

2.Predicted vs Actual category name.

I've achieved jac score of  0.02066706369836303 and mean jac score of 0.16669303166699856
and successfully made the recommendations of 5 pratilipi of userid,

1) 3263998672675492

2) 3264359729373860

3) 3264802291360420

4) 3308162227544740

5) 3314890925580964

I've attached 2 files 1 is for EDA and data cleaning and other one is for building model.
