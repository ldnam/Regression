This project, as part of the Advance Probability and Statistics course, aims to predict the number of new Covid-19 cases and new Covid-19 deaths using forward and backward regression methods.

The tasks include data pre-processing, applying both models and compare the results. 

While the method of forward regression applies the rule that we will iteratively put the most significant variable into the model until a pre-specified stopping rule is reached or all the variables under consideration are included in the model. Indeed, by fixing a threshold and finding the p-value of each variable, we will add those with low p-values (smaller than the threshold) and run the model again and again,
the backward regression starts with a full list of all variables and our task is to remove those with high p-values (larger than the threshold) and run the model with the new list. Then, we will do this process again until the all of the p-values are smaller than the threshold.

The results show that both algorithms share the same root mean square error, suggesting similar efficiency.
