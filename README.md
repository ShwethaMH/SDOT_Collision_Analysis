# SDOT Collision Analysis
## Introduction
SDOT (Seattle Department of Transportation) is responsible for maintaining the transportation infrastructure in the city of Seattle, including roads, bridges, and sidewalks. The department collects data on all collisions that occur in the city, including the severity of the collision, the conditions at the time of the collision (such as weather and lighting), and the number of people and vehicles involved. This data is publicly available and can be used to analyze collision patterns and identify areas for improvement in the transportation infrastructure.

In this project, we analyzed the SDOT collision data using machine learning techniques to develop models that can predict the severity of a collision based on various factors such as the weather, road conditions, and lighting. We used two machine learning algorithms, namely logistic regression and random forests, and compared their performance in terms of accuracy.

## Methodology
The methodology for this project can be broken down into the following steps:

### Data cleaning and preprocessing: We loaded the SDOT collision data from a CSV file and cleaned it by removing any duplicate or missing entries. We then preprocessed the data by encoding categorical variables, scaling numerical variables, and splitting the data into training and testing sets.

### Model selection and hyperparameter tuning: We selected two machine learning algorithms, logistic regression and random forests, and trained them on the preprocessed data. We tuned their hyperparameters using grid search and cross-validation.

### Model evaluation and comparison: We evaluated the performance of each model on the testing set using the accuracy metric. We compared the performance of each model to identify the best-performing algorithm for the SDOT collision data.

## Tools
The following tools and libraries were used in this project:

Python: programming language used to develop the machine learning models and data analysis scripts
Jupyter Notebook: interactive computing environment used to develop and document the code
pandas: library used for data manipulation and analysis
NumPy: library used for numerical computing and array operations
scikit-learn: library used for machine learning algorithms, preprocessing, and evaluation metrics

## Results
We found that the logistic regression and random forest models had an accuracy of 0.62 and 0.60, respectively, on the testing set.

## Conclusion and Future Work
In conclusion, we were able to develop machine learning models that can predict the severity of a collision based on various factors using the SDOT collision data. We found that the logistic regression model performed slightly better than the random forest model. However, both models had relatively low accuracy, indicating that there may be other factors that are important for predicting collision severity that were not captured in our analysis.

In future work, we could explore additional features that could improve the performance of the models, such as road gradient, traffic volume, and speed limits. Additionally, we could investigate the use of deep learning techniques, such as convolutional neural networks, to analyze images from traffic cameras and identify collision patterns in real-time. Furthermore, we could use the results of this analysis to inform the development of targeted interventions to improve the safety of the transportation infrastructure in Seattle.
