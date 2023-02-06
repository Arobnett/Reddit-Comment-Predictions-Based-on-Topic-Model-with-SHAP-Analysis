# Abstract 
Reddit is particularly an advantageous source of
data for surveying and sampling purposes. Unlike most other
prominent data sources where users usually interact, communicate,
and share data from identifiable profiles, Reddit is most commonly
used from an anonymous profile, allowing users a relatively
comfortable privacy to discuss and share more vulnerable thoughts
and ask more personal questions. This can be particularly useful
those interested in investigating sensitive topics such as mental
health. Organizations may want to investigate further the
discussions of these topics and the relation these topics may have
with other topics as a potential way to forecast the frequency of
communication regarding a particular topic to better guide policies
and actions. The purpose of this project is intended to apply the
relatively new Topic to Vector (Top2Vec) topic modeling algorithm
on a large data set of web scraped texts sampled from the comment
sections of the United States Air Force subreddit page as an
example. The example topic clusters most related to “Permanent
Change of Station (PCS)” and “Depression” are to be analyzed
using Correlation and Regression methods to investigate and
compare between potential types of relations between comments
from the designated “PCS” cluster to comments from the
designated “Depression” cluster. Predictions from the regression
model on the monthly occurrences of these cluster comments will
then be analyzed for model interpretability using a SHapley
Additive exPlanations Model (SHAP) to see which words stand out
as the most contributing features to the prediction model from the
scraped Reddit text sample data.
It was found between both of the data sets
that rather than using the monthly frequency of a particular
cluster to predict the monthly frequency of another cluster, it’s
a substantially better predictor to use the individual words of
the monthly comments as feature variables to predict the
monthly frequency of another cluster, which improved the average correlation score from the data sets from approximately 29% to appoximately 90%.

## Index Terms 
Top2Vec, Topic Modeling, Correlation, Linear
Regression, SHapley Additive exPlanations Model (SHAP), Cosine
Similarity, Euclidean, Distance Metric, United States Air Force,
Mental Health, Depression, Permanent Change of Station
