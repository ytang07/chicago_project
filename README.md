# chicago_project
Research Project associated with **STOR565 - Machine Learning** at UNC, Fall 2019.

## Group members 
* Erin Lyons
* Yujian Tang
* Norma Techarukpong
* Ryan Thomas
* Jason Yu

## Dataset
### Description
The dataset shows school level performance data for Chicago Public Schools for the 2012 school year. The dataset describes the performance of individuals whom are identified by a school ID number. It then describes their school and scores the school on various criteria. Some of the characteristics are qualitative while others are quantitative. It then includes some indicators of how prepared they are for college and if they are staying on track their freshman year of higher education. 

### Source
We found our dataset on data.gov. The direct link is provided here: https://catalog.data.gov/dataset/chicago-public-schools-progress-report-cards-2011-2012-8a7a5 

## Motivations and goals
We wanted to find a dataset that both interested us as a group and provided sufficient data to work with in order to reach the project goals. Education is an important issue that has implications for a city’s economy, work force, and social structure. We thought this dataset would be really interesting to see how various academic indicators truly affect higher education success. 

Some of our goals are to explore and answer the following questions: 
* Evaluate what factors will cause a school to improve
* How to predict a school’s health rating
* How to predict teacher attendance
* How different schools are distinguished and separated based on numerical ratings 
* How we can categorize schools based on unsupervised learning techniques
* Overarching research question: How can Chicago public schools be improved?

## Preliminary ideas on techniques to apply
* PCA/PCR
   * PCA could potentially help us figure out what variance separates different types of school categories.
* Various types of regression methods
   * LASSO
   * Ridge
   * OLS
* Classification- ways to classify schools in the Chicago schools
   * Binary prediction of whether a school has met sufficient improvement that school year (logistic regression)
   * Classification that guesses a school’s area based on multiple other predictors (will choose best between KNN, LDA, and QDA)
