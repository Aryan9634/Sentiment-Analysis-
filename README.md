# Sentiment Analysis using ML algorithms and Lexicon-based approach

The sentiment analysis process involves the implementation of both machine learning algorithms and a lexicon-based approach. The steps followed in this analysis are as follows:

Data Pre-processing: To ensure data quality, various techniques such as null and duplicate data processing, stemming, stop-word removal, and formatting are applied. Pandas and NLTK libraries are employed for this purpose.

Exploratory Data Analysis (EDA): Data visualization techniques utilizing Pandas, Seaborn, and Matplotlib are employed to gain insights into the data.

Data Transformation: The Tf-idf Vectorizer is utilized for transforming the data, and a comparative analysis is conducted between LDA and SelectKbest methods for feature selection. This approach effectively addresses overfitting issues.

Modelling and Training: A Voting Classifier is employed with a range of estimators, including KNN, SVC, MultinomialNB, GaussianNB, BernoulliNB, LogisticRegression, RandomForestClassifier, and GradientBoostingClassifier. Hyperparameter optimization techniques are applied, and the models are trained using stratified K-fold cross-validation.

Application Development: The application is developed using HTML and CSS for the frontend, and Flask is utilized for the backend.

Note: It is important to note that the primary prediction, which relies on the utilization of the Vader Sentiment Intensity Analyzer, holds precedence over the model-based prediction.

demo : https://www.linkedin.com/posts/activity-7072898470327521280-DnVR?utm_source=share&utm_medium=member_desktop

