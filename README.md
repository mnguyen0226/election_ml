# County Presidential Election Results Prediction Based On Fundamentals: A Comparison

![](https://github.com/mnguyen0226/ece_5424_project/blob/main/imgs/cover_img.jpg)

### About 
In our project, we highlight the potential for predicting the United States presidential election outcomes at the county level based on the fundamental variables acquired from American Community Survey data (ACS). Fundamentals refer to variables independent of the current election rhetoric, the campaign performance of a candidate immediately before an election, or social media posts. Fundamental variables include individuals' annual income, annual total family income, age, gender, marital status, race, citizenship status, language spoken at home, education level, and employment status at the individual level. Using these fundamental variables, we aim to determine whether we can predict election outcomes.

### Notebooks
- Data Processing & Analysis
  - [Data Preprocessing](https://github.com/mnguyen0226/ece_5424_project/blob/main/src/DataPreprocessing.ipynb)
  - [Data Exploration](https://github.com/mnguyen0226/ece_5424_project/blob/main/src/data_exploration.ipynb)
  - [Feature Analysis](https://github.com/mnguyen0226/ece_5424_project/blob/main/src/features_analysis.ipynb)
  - [Feature Importance](https://github.com/mnguyen0226/ece_5424_project/blob/main/src/get_important_features.ipynb)
- Model Performance with Full Dataset
  - [Multi-layer Perceptron - No Feature Selection](https://github.com/mnguyen0226/ece_5424_project/blob/main/src/us_election_prediction_mlp_no_feature_selection.ipynb)
  - [Support Vector Machine - No Feature Selection](https://github.com/mnguyen0226/ece_5424_project/blob/main/src/us_election_prediction_svm_no_feature_selection.ipynb)
  - [Decision Tree - No Feature Selection](https://github.com/mnguyen0226/ece_5424_project/blob/main/src/us_election_prediction_decision_tree_no_feature_selection.ipynb)
  - [Random Forest - No Feature Selection](https://github.com/mnguyen0226/ece_5424_project/blob/main/src/us_election_prediction_random_forest_no_feature_selection.ipynb)
- Model Performance with Feature-selected Dataset
  - [Logistic Regression - With Feature Selection](https://github.com/mnguyen0226/ece_5424_project/blob/main/src/us_election_prediction_logistic_with_feature_selection.ipynb)
  - [Multi-layer Perceptron - With Feature Selection](https://github.com/mnguyen0226/ece_5424_project/blob/main/src/us_election_prediction_mlp_with_feature_selection.ipynb)
  - [Support Vector Machine - With Feature Selection](https://github.com/mnguyen0226/ece_5424_project/blob/main/src/us_election_prediction_logistic_with_feature_selection.ipynb)

### Results

Decision Tree Election Prediction Performance
![](https://github.com/mnguyen0226/ece_5424_project/blob/main/imgs/dt_performance.png)

Multi-layer Perceptron Election Prediction Performance
![](https://github.com/mnguyen0226/ece_5424_project/blob/main/imgs/mlp_performance.png)

Random Forest Election Prediction Performance
![](https://github.com/mnguyen0226/ece_5424_project/blob/main/imgs/rf_performance.png)

Support Vector Machine Election Prediction Performance
![](https://github.com/mnguyen0226/ece_5424_project/blob/main/imgs/svm_performance.png)