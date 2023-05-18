Analysis Overview
In this analysis, the primary focus was to develop a deep learning neural network model that could effectively tackle a classification challenge. my goal revolved around forecasting the probability of a charitable organization achieving funding success, leveraging a diverse range of unique characteristics.

- Data Preprocessing
1. What variable(s) are the target(s) for your model?
The model's dependent variable, represented as y = application_df["IS_SUCCESSFUL"].values, signifies the result indicating whether a charitable organization successfully secures funding.
2. What variable(s) are the features for your model?
For the model, all variables were employed as features except for y = application_df["IS_SUCCESSFUL"].values, which served as the dependent variable.
3. What variable(s) should be removed from the input data because they are neither targets nor features?
To ensure optimal performance, the columns "EIN" and "NAME" were omitted from the input data due to their limited value as targets or features.

- Compiling, Training, and Evaluating the Model
1. How many neurons, layers, and activation functions did you select for your neural network model, and why?
2. Were you able to achieve the target model performance?
3. What steps did you take in your attempts to increase model performance?


Summary 
Unfortunately, I was unable to obtain the model accuracy for predicting the success of charity organizations in receiving funding. However, the deep learning neural network model exhibited promising outcomes. It demonstrated the potential to effectively classify organizations, although the specific accuracy rate remains unknown.

To explore alternative avenues, it is advisable to consider ensemble methods like Random Forest. Through the utilization of ensemble methods and the implementation of feature engineering techniques, a stronger and more precise model can be constructed.






