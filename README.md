
# Basic problem solving using machine learning

The notebooks are from the course Introduction to Machine Learning.

1.  Explanatory Data Analysis notebook focuses on a voluntary survey of IT workers about mental health.
2.  Regression notebook attempts to use a dataset of student grades as a regression problem.
3.  The Classification notebook deals with the sentiment of Amazon and Tweets reviews.
4.  The Clustering notebook considers whether it is possible to classify articles according to their authors using unsupervised learning and the k-means algorithm.

# Key takeaways

## Mental health in IT - Explanatory Data Analysis

-   Data is collected from a voluntary survey about mental health in IT workplaces.
-   Due to voluntary responses, the data is biased.
-   Voluntary response samples oversample people who have strong opinions and undersample people who don't have much interest in the research topic.
-   Respondents felt more stigmatized over mental health matters than physical health.
-   Respondents still recognize mental health treatment as something stigmatized in society.
-   More respondents took treatment if they could stay anonymous.
-   The chi-square test confirmed that mental health benefits provided by an employer encourage employees to seek treatment.

## Portugal students' grades - Regression

-   The dataset approaches student achievement in secondary education of two Portuguese schools.
-   Data attributes include students' past grades, demographic, family, social, and school-related features.
-   It was collected by using school reports and questionnaires.
-   Common machine learning algorithms (linear regression, polynomial regression) have rather poor performance on this dataset.
-   The error decreases as we have more past grades to use in the regression.
-   It would be better to do classification (target variable would be if the student passes the class) than regression on its final grade.

## Amazon sentiment analysis - Classification #1

-   The dataset is pleasant to work with.
-   It includes Amazon reviews on some baby products.
-   English language has already many out-of-the-box preprocessing solutions included in many libraries.
-   Logistic Regression could achieve a 0.95 AUC score.

## Twitter hate speech analysis - Classification #2

-   The task is binary classification to detect hate speech in Polish language tweets.
-   Preprocessing tweets is a harder task. There are no easy-to-use stemming/lemmatization libraries for the Polish language, and the language is way more informal and grammar error-prone.
-   The dataset is highly imbalanced (90% vs. 10%).
-   Using basic algorithms like Logistic Regression gives about a 0.6 AUC score.
-   Oversampling the minority class using SMOTE increases the accuracy to a 0.71 AUC score while using the Naive Bayes Classifier.# Basic problem solving using machine learning

The notebooks are from the course Introduction to Machine Learning.

1.  Explanatory Data Analysis notebook focuses on a voluntary survey of IT workers about mental health.
2.  Regression notebook attempts to use a dataset of student grades as a regression problem.
3.  The Classification notebook deals with the sentiment of Amazon and Tweets reviews.
4.  The Clustering notebook considers whether it is possible to classify articles according to their authors using unsupervised learning and the k-means algorithm.

# Key takeaways

## Mental health in IT - Explanatory Data Analysis

-   Data is collected from a voluntary survey about mental health in IT workplaces.
-   Due to voluntary responses, the data is biased.
-   Voluntary response samples oversample people who have strong opinions and undersample people who don't have much interest in the research topic.
-   Respondents felt more stigmatized over mental health matters than physical health.
-   Respondents still recognize mental health treatment as something stigmatized in society.
-   More respondents took treatment if they could stay anonymous.
-   The chi-square test confirmed that mental health benefits provided by an employer encourage employees to seek treatment.

## Portugal students' grades - Regression

-   The dataset approaches student achievement in secondary education of two Portuguese schools.
-   Data attributes include students' past grades, demographic, family, social, and school-related features.
-   It was collected by using school reports and questionnaires.
-   Common machine learning algorithms (linear regression, polynomial regression) have rather poor performance on this dataset.
-   The error decreases as we have more past grades to use in the regression.
-   It would be better to do classification (target variable would be if the student passes the class) than regression on its final grade.

## Amazon sentiment analysis - Classification #1

-   The dataset is pleasant to work with.
-   It includes Amazon reviews on some baby products.
-   English language has already many out-of-the-box preprocessing solutions included in many libraries.
-   Logistic Regression could achieve a 0.95 AUC score.

## Twitter hate speech analysis - Classification #2

-   The task is binary classification to detect hate speech in Polish language tweets.
-   Preprocessing tweets is a harder task. There are no easy-to-use stemming/lemmatization libraries for the Polish language, and the language is way more informal and grammar error-prone.
-   The dataset is highly imbalanced (90% vs. 10%).
-   Using basic algorithms like Logistic Regression gives about a 0.6 AUC score.
-   Oversampling the minority class using SMOTE increases the accuracy to a 0.71 AUC score while using the Naive Bayes Classifier.
