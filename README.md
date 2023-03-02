# Predicting Job Shift using Linkedin Tech-Talent Data

Includes detailed solution of [__Garanti BBVA Data Camp__](https://www.kaggle.com/competitions/garanti-bbva-data-camp). I attended the competition solo and ranked 14th(top %9) out of 210 competitors and 174 teams. 

## Solution Pipeline
* Cleaning education, skill, language, work experiences datasets which are included with erroneous data at a high rate and fixing a few problems on train - test sets.
* Feature engineering followed by imputation and encoding.
* Using Random Forest cross-validation training and stacking, according to model selection during the competition and also with the best dataset decided by various feature selection techniques.

__Main solution can be found both in English and Turkish, with the added bonus/unused work performed during competition.__
***
#### Bonus content:
__I also added:__
* The mentioned fi_forward_feature_selector function that I wrote and used to create the dataset that got me the second best private score out of my three final day submissions.
* The codes of HalvingGridSearch and Optuna, when I was in search of tuning hyperparameters faster than standart GridSearch. While GridSearchCV does not use any optimization algorithm and tries all the combinations from the given parameter grid, HalvingGridSearch uses and algorithm called successive halving that makes it approximately 4x faster.
* The code of training curves with Yellowbrick library, to detect how hyperparameter values effect the model, and by that minimize the range of hyperparameters given to HalvingGridSearch to get even faster results.
* The code that I used to scrape an external data but unfortunately seemed unimportant after modelling and so remained unused during competition.



https://www.kaggle.com/so24def
