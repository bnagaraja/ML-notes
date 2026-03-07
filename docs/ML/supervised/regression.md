# Regression
A regression model predicts a numeric value. For example, a weather model that predicts the amount of rain, in inches or millimeters, is a regression model. 

???+ examples "📌 Regression Scenarios"

    | Scenario            | Possible Input Data                                                                                                        | Numeric Prediction                  |
    |--------------------|---------------------------------------------------------------------------------------------------------------------------|------------------------------------|
    | Future House Price  | Square footage, zip code, number of bedrooms and bathrooms, lot size, mortgage interest rate, property tax rate, construction costs, number of homes for sale in the area | The price of the home               |
    | Future Ride Time    | Historical traffic conditions (smartphones, traffic sensors, ride-hailing apps), distance from destination, weather conditions | The time in minutes and seconds to arrive at a destination |


##Types of regression models: 

    - Linear regression, which finds the line that best fits label values to features.

    - Logistic regression, which generates a probability between 0.0 and 1.0 that a system typically then maps to a class prediction.

??? notes "Note:"
    Not every model that outputs numerical predictions is a regression model. In some cases, a numeric prediction is really just a classification model that happens to have numeric class names. For example, a model that predicts a numeric postal code is a classification model, not a regression model. 

##### **Classification**
Classification models predict the likelihood that something belongs to a category. Unlike regression models, whose output is a number, classification models output a value that states whether or not something belongs to a particular category. 

For example, classification models are used to predict if an email is spam or if a photo contains a cat. 

Classification models are divided into two groups: binary classification and multiclass classification.

- Binary classification models output a value from a class that contains only two values, for example, a model that outputs either rain or no rain.

- Multiclass classification models output a value from a class that contains more than two values, for example, a model that can output either rain, hail, snow, or sleet. 

??? example "Example:"

    | Study Hours | Pass (Yes=1, No=0) |
    | ----------- | ------------------ |
    | 2           | 0                  |
    | 5           | 1                  |
    | 3           | 0                  |
    | 7           | 1                  |

    - Input: Study Hours
    - Output: Pass or Fail
    - The model learns a rule: If study hours > 4 → Pass; otherwise → Fail
    - Now, given a new student with 6 study hours, the model predicts Pass.

**Advantages:**

- Produces accurate predictions when trained on good data.

- Easy to evaluate with metrics like accuracy, precision, recall, or RMSE.

**Disadvantages:**

- Requires a large amount of labeled data.

- Can overfit if the model is too complex for the given dataset.

-----

???+ tip "Short Notes"
    The model learns from labeled data (input + correct output).

    Used for: Prediction

    Examples:

        - Spam detection

        - House price prediction

        - Disease prediction

    Common Algorithms:

        - Linear Regression

        - Logistic Regression

        - Decision Trees

        - Support Vector Machines