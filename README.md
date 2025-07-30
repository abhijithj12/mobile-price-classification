Mobile Price Classification (Random Forest)

Hi there! This is a simple machine learning project where I built a model to predict the price range of a mobile phone based on its features like battery power, RAM, camera quality, and more.

 About the Dataset

    File name: mobile_price.csv

    Each row represents a mobile phone with details like screen size, memory, etc.

    The goal is to predict the price_range:

        0 = Low cost

        1 = Medium cost

        2 = High cost

        3 = Very high cost

 What I Did

    Loaded and explored the dataset.

    Preprocessed the data (scaled the features using StandardScaler).

    Split the data into training and testing sets.

    Trained a Random Forest Classifier.

    Evaluated it using accuracy and confusion matrix.

 My Results

    ✅ The model gave an accuracy of ~89% on the test data.

    That means it correctly predicts the price range most of the time!

Tools Used

    Python

    Pandas

    Scikit-learn

    Matplotlib & Seaborn

What I Learned

This was a good hands-on exercise to understand:

    How classification works

    Importance of scaling data before training

    How Random Forest handles multi-class classification

 What’s Next

    Try out GridSearchCV to tune the Random Forest.

    Use feature_importances_ to see which features matter most.

    Compare this model with other algorithms like XGBoost.
