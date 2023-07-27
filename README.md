# Predicting Employee Churn using Linkedin Tech-Talent Data

__Problem type: Binary Classification__

Includes detailed solution of [__Garanti BBVA Data Camp__](https://www.kaggle.com/competitions/garanti-bbva-data-camp). I attended the competition solo and ranked 14th(top %9) out of 210 competitors and 174 teams. 

## Solution
* Cleaning education, skill, language, work experiences datasets which are included with erroneous data at a high rate and fixing a few problems on train - test sets.
* Feature engineering, followed by imputation and encoding.
* Using Random Forest cross-validation training and stacking, according to model selection during the competition and also with the best dataset decided by various feature selection techniques.

__Main solution can be found both in English and Turkish, with the added bonus/unused work performed during competition.__

***
#### Bonus
_I also added;_
* The mentioned fi_forward_feature_selector function that I wrote and used to create the dataset that got me the second best private score out of my three final day submissions.
* The codes of HalvingGridSearch, TuneGridSearch and Optuna, when I was in search of tuning hyperparameters faster than standart GridSearch. While GridSearchCV does not use any optimization algorithm and tries all the combinations from the given parameter grid, HalvingGridSearch uses an algorithm called successive halving that makes it approximately 4x faster. Also TuneGridSearch is another faster alternative.
* The code of training curves with Yellowbrick library, to detect how hyperparameter values effect the model, and by that minimize the range of hyperparameters given to HalvingGridSearch to get even faster results.
* The code that I used to scrape an external data but unfortunately seemed unimportant after modelling and so remained unused during competition.
***

#### External Data/Sources

* [Anıl Öztürk](https://github.com/nlztrk)'s well-explained Kaggle notebooks and competition solutions, especially [this competition solution](https://www.kaggle.com/code/nlztrk/3rd-place-solution-0-51376-0-47111?scriptVersionId=114222767&cellId=44) where I learned the method of training the model with CV and stacking.
* In-demand skills shared on Linkedin blog for years of [2018](https://www.linkedin.com/business/learning/blog/top-skills-and-courses/the-skills-companies-need-most-in-2018-and-the-courses-to-get), [2019](https://www.linkedin.com/business/learning/blog/top-skills-and-courses/the-skills-companies-need-most-in-2019-and-how-to-learn-them),[2020](https://www.linkedin.com/business/learning/blog/learning-and-development/most-in-demand-skills-2020)
* Popular/useful languages shared on Linkedin blog for years of [2018](https://www.linkedin.com/pulse/7-most-useful-languages-learn-2018-nikola-gizarovski/), [2019](https://www.linkedin.com/pulse/top-5-internet-languages-2019-matthew-nelson/), [2020](https://www.linkedin.com/pulse/15-best-languages-learn-2020-ofer-tirosh/)
* [World universities data](https://github.com/endSly/world-universities-csv), [Turkey cities data](https://github.com/yigith/TurkiyeSehirlerBolgeler), [Turkey districts data](https://github.com/volkansenturk/turkiye-iller-ilceler/blob/master/csvs/ilce.csv)
***





https://www.kaggle.com/so24def
