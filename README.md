# Improving-the-Expected-Goals-xG-Model
Expected Goals: The most popular football analytics metric that models the chances of goal from a shot/header taken.

Expected Goals: The most popular football analytics metric, and by far one of the most essential one, as the intent of all other metrics of Valuing Estimated Probabilities for On Ball Actions, eXpected Threats, etc is to result in quality creation of chances, and shots that drives the probability of shot conversion at goal higher - A probabilistic classification problem.

I have designed a novel and improved methodology to model expected goals with nearly 60% lesser data, achieving a ~90% ROC AUC score that is 12% better classification efficiency. Optimised model reliability to ~95% that is 2.5% better calibrated probabilities with an impressive 2x jump in model fit using lesser training data.

Process :
1. Identify data source (StatsBomb Open Data, mplsoccer API, Understat)
2. Develope a pipeline to extract raw data, perform research.
3. Develope a data processing flow to process raw data into modelling features based on their documentation.
4. Perform Exploratory Data Analysis, advanced insightful visualisation, Outlier Detection and Transformations.
5. Develope multiple probabilistic classification model on different methodologies and algorithms to improve considered evaluation benchmarks.
6. Perform Model Calibration.
7. Model Evaluation and Conclusions.
