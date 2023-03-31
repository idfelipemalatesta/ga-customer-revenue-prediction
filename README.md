# Google Analytics Customer Revenue Prediction

## About the repository
This project is a kaggle community competition [Google Analytics Customer Revenue Prediction](https://www.kaggle.com/competitions/ga-customer-revenue-prediction/overview). In this competition, you’re challenged to analyze a Google Merchandise Store (also known as GStore, where Google swag is sold) customer dataset to predict revenue per customer. 

Submissions are scored on the root mean squared error (RMSE).

### Project content:

1. Data Preparation <br>
  1.1 Import libraries <br>
  1.2 Loading the dataset <br>
2. Data Analysis/Cleaning <br>
  2.1 Constant Variables <br>
	2.2 Missing Data <br>
  2.3 Target Variable <br>
3. Feature Engineering <br>
	3.1 Removing some variables <br>
	3.2 Changing data types <br>
	3.3 Log Transformation <br>
  3.4 Label Encoder <br>
4. Model Training <br>
  4.1 Split Data <br>
	4.2 Cross Validation with LGBMRegressor <br>
	4.3 Hyperparameter tuning (Random search - skopt) <br>
  4.4 Feature Importance (Plot) <br>
5. Inference and Submission <br>
  5.1 Inference on test data <br>
  5.2 Submission <br>
6. References

**Private Score: 0.88965**
