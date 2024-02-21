# Linear Regression Model for calculating Customer Credit Scores

Project aimed at creating, testing and evaluating an example of a Linear Regression model for calculating customer Credit Scores.

## Project phases

1. Exploratory data analysis

    * Verification of the general characteristics of the data;
    * Checking for missing data;
    * Checking for inconsistent data;
    * Attribute engineering.
2. Data visualization

    * Creation of tables and graphs;
3. Data transformation

    * Creation of new data columns;
    * Treatment of null or incorrect data;
    * Deletion of irrelevant data;
    * One Hot Encoding (adaptation of types according to the algorithm);
    * Balancing the target variable and predictors;
    * Separation of training and testing data;
    * Normalization and/or Standardization of data;
4. Creating, Testing and Evaluating the Linear Regression Model

    * Training the Linear Regression model;
    * Predictor test;
    * Evaluation of the Linear Regression model;

## Technologies Used

This project was executed using the Python language in the Jupyter Notebook format. The libraries Pandas (Loading, Cleaning and Data Analysis), Matplotlib and Seaborn (Data visualization and graph generation), Sklearn (Creation, training and evaluation of the Machine Learning model), Git (Code versioning) and the The chosen IDE was Visual Studio Code, running on Debian Linux.

**Related links:**

* [Debian Linux](https://www.debian.org/index.pt.html)
* [VSCode](https://code.visualstudio.com/)
* [Python](https://www.python.org/)
* [Jupyter](https://jupyter.org/)
* [Pandas](https://pandas.pydata.org/)
* [Matplotlib](https://matplotlib.org/)
* [Seaborn](https://seaborn.pydata.org/#)
   [Sklearn](https://scikit-learn.org/stable/)
* [Git](https://git-scm.com/)

### Required Dependencies and Versions

The software and libraries used in the projects had the following versions:

* Python - Version: 3.11.5
* Pandas - Version: 2.2.0
* Matplotlib - Version: 3.8.3 (matplotlib-inline: 0.1.6)
* Seaborn - Version: 0.13.2
* Scikit-learn - Version: 1.4.0

**Note:** for more details see the "requirements.txt" file

## How to run the project

To run the project the following methods can be used:

#### *Method 1:* Download the project

**Step 1:**

On the project's main page [https://github.com/thaleswillreis/Modelo-ML-Credit-Score-v1.git](https://github.com/thaleswillreis/Modelo-ML-Credit-Score-v1.git ), look for the green button labeled "<> Code".

**Step 2:**

Click "Download ZIP"

**Step 3:**

Unzip the folder you finished downloading.

**Step 4:**

Open projects containing the ".ipynb" extension.

#### *Method 2:* Clone the repository

Note: Before proceeding with this process, make sure that GitHub is properly configured on your computer.

**Step 1:**

Create a folder that you have write permissions to.

**Step 2:**

Open a terminal from the newly created folder or navigate to it through the terminal.

**Step 3:**

On the project's main page [https://github.com/thaleswillreis/Modelo-ML-Credit-Score-v1.git](https://github.com/thaleswillreis/Modelo-ML-Credit-Score-v1.git ), look for the green button labeled "<> Code".

**Step 4:**

Copy the repository URL.

**Step 5:**

In the terminal type:

```
git Clone https://github.com/thaleswillreis/Modelo-ML-Credit-Score-v1.git
```

Wait for the repository cloning to finish.

**Step 6:**

Open projects containing the ".ipynb" extension.

## Problems faced

The code may face problems when running using different versions of languages and libraries. Make sure that the versions listed in the "Required Dependencies and Versions" item are correctly installed.

If there is already a development environment with different versions in use on the machine used, a good alternative would be to create a virtual development environment. If in doubt, follow the documentation link.
[Virtual environments and packages](https://docs.python.org/pt-br/3/tutorial/venv.html)

## Results Obtained (Evaluation Metrics)

**Coefficient of Determination (R²):** 0.3031101484841182
**Mean Absolute Error (MAE):** 20.426584637244353
**Mean Square Error (MSE):** 519.6339828679319
**Square Root Mean Square Error (RMSE):** 22.795481632725636

#### About Assessment metrics:

* *Coefficient of Determination (R²):*

R² is a metric that ranges from 0 to 1, where 1 indicates that the model explains all the variability in the data. In this case, an R² of 0.3031 means that the model explains approximately 30.31% of the variability in the test data. A value above 0.3 can be considered moderate, but logically this depends on the context and expectations for the specific problem.

* *Mean Absolute Error (MAE):*

It is the average of the absolute differences between the model predictions and the actual values. In this case, the MAE of 20.43 indicates that, on average, the model predictions have an absolute deviation of 20.43 units from the actual values.

* *Mean Square Error (MSE):*

It is the mean of the squares of the differences between the model predictions and the actual values. In this case, the MSE of 519.63 indicates that, on average, the square of the deviation of the forecasts from the actual values is 519.63.

* *Square Root Mean Square Error (RMSE):*

It is the square root of the MSE, and provides a measure of the average error in terms of the same unit as the response variable. In this case, the RMSE of 22.80 indicates that, on average, the predictions have a deviation of approximately 22.80 units from the actual values.

## Conclusion

Although, as I explained previously, an interpretation of "satisfactory" or "not satisfactory" depends on the specific context of the problem and expectations regarding the final result, the construction and evaluation of the Linear Regression model initially proposed was successful. . However, we must emphasize that during tests with the data used, the model achieved only average performance and proved insufficient to be used in production as it is, requiring further improvement of the model.

## Next steps

* *Explore More Complex Models:*

Consider exploring more complex models, such as decision tree models, random forests, or gradient boosting models, to see if they can capture more intricate patterns in the data.

* *Features Engineering:*

Evaluate whether the inclusion of new relevant features or the transformation of existing features can improve model performance.

* *Hyperparameter Tuning:*

Experiment with tuning the model's hyperparameters to optimize performance. This can be done using techniques such as cross-validation.

* *Other models:*

Consider exploring different models to see which fits the data best.

## Final considerations

If this content is useful to you, you have any questions or want to contribute to some improvement, leave your comment or contribute to the project.