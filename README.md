# Kaggle Competitions Notebooks

This repository contains my personal notebooks for various Kaggle competitions. Each notebook is a self-contained solution exploring data analysis, feature engineering, and modeling techniques relevant to the specific competition's challenge. They are all high-quality notebooks containing commentary and visualizations for new data scientists.

## Competitions

- [Titanic](https://www.kaggle.com/code/adends/xgboost-for-titanic-competition)
  - **Overview**: A classing introductory machine learning challenge that tasks participants with predicting whether a given passenger survived on the Titanic.
  - **Highlights**: In this competition, I explore the dataset performing necessary preprocessing and feature engineering steps which is supported with visualizations and commentary. The data is then fed into a machine learning pipeline where it undergoes additional preprocessing steps and fitted to our data to make predictions. We use Gradient Boosting (XGBoost) that is tuned with optimal parameters to acheive a high competition standing and community support.
- [Spaceship Titanic](https://www.kaggle.com/code/adends/spaceship-titanic-competition-w-ensemble-methods)
  - **Overview**: A spinoff of the classical Titanic competition, you are tasked with predicting whether a given passenger is transported to an alternate dimension. 
  - **Highlights**: In this competition, I again explore the dataset performing necessary preprocessing and feature engineering steps enriching the notebook with visualizations and commentary. It is then fed into a machine learning pipeline where it undergoes additional proeprocessing steps and is fit to different ensemble (e.g. Random Forest, XGBoost) and linear methods (e.g. Logistic Regression). In the final iteration, I utilize a tuned Random Forest model to acheive a high competition standing and community support.
- [Store Sales](NONE)
  - **Overview**: A problem where you are faced with forecasting Store Sales in Ecuador using historic time-series data.
  - **Highlights**: 
- [House Prices](https://www.kaggle.com/code/adends/neural-network-with-embeddings-for-house-prices)
  - **Overview**: A regression problem where you must predict the sale price of a house given some qualities about it.
  - **Highlights**: In this competition, I perform various preprocessing and feature engineering steps before forming my data into tensors. These tensors are then fed into a Feed-Forward Neural Network with various optimizations to predict house prices. The neural network implements both Embedding and Linear layers to better capture the meaning of the categorical variables. This notebook is supported with commentary and visualizations to help readers comprehend. The result is a high competition standing and community support.
- [Disaster Tweets](https://www.kaggle.com/code/adends/commentary-on-bert-with-pytorch)
  - **Overview**: A NLP problem where you are tasked with identifying which Tweets are describing a real Natural Disaster.
  - **Highlights**: In this competition I perform data preprocessing and feature engineering to create insightful numeric features to support our given categorical features. These features are then fed into a Hybrid Neural Network that utilizes BERT for the categorical features and a Feed-Forward Neural Network for the numeric features. Together this creates a robust network that acheieved a top score in the competition. This notebook is also supported with commentary on approaches and rich visualizations.
- [Digit Recognizer](https://www.kaggle.com/code/adends/digit-recognizer-with-pytorch)
  - **Overview**: A classic Computer Vision problem where you are tasked with classifying hand-written digit images.
  - **Highlights**: In this competition, I leveraged PyTorch to engineer a sophisticated Convolutional Neural Network (CNN) tailored for high-accuracy digit recognition. The approach included strategic data augmentation to improve generalization, and a robust training regimen featuring KFold cross-validation, early stopping, and adaptive learning rate scheduling for peak performance. My solution emphasized efficiency in data processing and model optimization, setting a benchmark for future competitions.
- [Regression with Abalone Dataset](https://www.kaggle.com/code/adends/diving-deep-into-abalone)
  - **Overview**: A regression problem where you are tasked with predicting the rings (age) of an abalone given some if it's other features.
  - **Highlights**: In the 'Diving Deep for Abalone' competition, I used data visualization libraries to uncover insights into abalone ages, focusing on distribution, correlation, and categorical differences through histograms, pair plots, and 3D scatter plots. These visual analyses informed my use of ensemble methods, including CatBoost, LightGBM, and XGBoost, driving my strategy for predictive accuracy.



