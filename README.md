Jack Olson

## Project 2: Predicting House Prices

### Summary
>1.	Model v1: Linear regression using four features
>2.	Model v2: Using feature engineering to improve upon Model v1
>3.	Possibilities for future improvements

### Overview
- Part 1: Model v1
    * Model v1 is a linear regression based on four features: 'Overall Quality', 'Above Ground Living Area', 'Garage Area', and 'Year Built'
      * These features were selected because they are highly correlated with price and are not highly correlated with each other
    * Model v1 Successes:
      * Easy to understand (only four features, simple linear regresion)
      * Little correlation between features
      * Normal residuals
      * Similar training score and test score (only sligtly overfit)
      * Coefficients are easy to interperet
    * Areas for improving Model v1:
      * No feature engineering
      * Predictive accuracy could be improved
- Part 2: Model v2
  * Model v2 uses the same four features as Model v1 but employs polynomial features to consider the interactions between those features
  * Model v2 Successes:
    * Increased predictive accuracy
    * Sticking with four variables keeps it relatively easy to understand and avoids multicollinearity issues
- Part 3: Possibilities for future improvements
  * Use more input variables
    * Advantage of this would be increased accuracy
    * Disadvantages would be increased complexity, possibility of over fitness, multicollinearity issues
  * Use Ridge, Lasso, or ElasticNet
    * Advantage would be a big increase in predictive accuracy
    * Disadvantage would be increased complexity, making the model harder to understand for users
- Conclusion
  * The goal of this Kaggle competition was to make a model that is as accurate as possible. But often it's best to consider the user of the model. Sometimes a simpler, more understandable model is better