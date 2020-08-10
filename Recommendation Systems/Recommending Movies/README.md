# Evaluating Recommender Systems
## Accuracy Metrics (Low error is good)
<li> MSE (Mean Square Error) (less is better)
<li> RMSE (Root Mean Square Error) (less is better)</li>
![image](https://user-images.githubusercontent.com/40051540/89826957-9b57a100-db1c-11ea-88af-4cc07bac844c.png)
Penalizes you more when your rating predictions are way off 
  
	User-focused metric
Find top N recommendation for a user and see if they are movies the user rated, if, so it is a hit!
	Hit rate =   hits/users (higher is better)
Leave one out cross validation 
	Average Reciprocal Hit Rate (higher is better)
Takes into account how far up your hit is.
 
	Cumulative Hit Rate (higher is better)– Don’t include predictions below a certain threshold 
	Rating Hit Rate (higher is better) – keep track of hit rate for each unique rating value. Hits for each rating type.
	Coverage (Higher is better) - % of user, item pairs that can be predicted 
	Diversity (Higher means more diverse) – How broad a variety of items the recommender system recommends
(1 – S) S- average similarity between recommendation pairs.
This requires lot of compute time. In the real you would sample the data to compute this.
	Novelty (Higher means more novel) – Mean popularity rank of recommended items
	Churn – How often do recommendations change?
	Responsiveness - How quickly does user new user behavior influence recommendations?
	Online A/B tests
	Perceived quality – ask users feedback about the recommendations
Focusing on accuracy alone is not helpful. You need to do AB testing and see how it works in the real world
