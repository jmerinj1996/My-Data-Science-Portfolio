# Evaluating Recommender Systems
## Accuracy Metrics (Low error is good)
### <li> MSE (Mean Square Error) (less is better)</li>
### <li> RMSE (Root Mean Square Error) (less is better)</li>
Penalizes you more when your rating predictions are way off 

## User-focused metric
<p>Find top N recommendation for a user and see if they are movies the user rated, if, so it is a hit!</p>

#### Hit rate
Hit rate =   hits/users (higher is better)
Leave one out cross validation 

#### Average Reciprocal Hit Rate (higher is better)
Takes into account how far up your hit is.

#### Cumulative Hit Rate (higher is better)
Don’t include predictions below a certain threshold </li>

#### Rating Hit Rate (higher is better)
Keep track of hit rate for each unique rating value. Hits for each rating type.</li>

## Coverage (Higher is better)
% of user, item pairs that can be predicted 

## Diversity (Higher means more diverse)
<li>How broad a variety of items the recommender system recommends
<li>(1 – S) S- average similarity between recommendation pairs.
<li>This requires lot of compute time. In the real you would sample the data to compute this.</li>

## Novelty (Higher means more novel)
Mean popularity rank of recommended items

## Churn
How often do recommendations change?

## Responsiveness
How quickly does user new user behavior influence recommendations?

## Online A/B tests

## Perceived quality
<li>Ask users feedback about the recommendations
<li>Focusing on accuracy alone is not helpful. You need to do AB testing and see how it works in the real world
