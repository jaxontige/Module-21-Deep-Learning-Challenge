# Module-21-Deep-Learning-Challenge
Corb and I worked togehter on this assignment. We used class slides and challenges, Chat GPT, GitHub, and Google as resources for this one

Overview
  The purpose of this analysis was to build a neural networks in order to identify successful applicants for Alphabet Soup in order to streamline selection.

Results

  Data Preprocessing
  
  What variable(s) are the target(s) for your model?
  - The targe variable is "IS_SUCCESSFUL".
    
  What variable(s) are the features for your model?
  - We used several metadata columns
  
  What variable(s) should be removed from the input data because they are neither targets nor features?
  - We removed "EIN" and "NAME" columns from the input data
  
Compiling, Training, and Evaluating the Model

  How many neurons, layers, and activation functions did you select for your neural network model, and why?
  - We used 2 nuerons
  - First we used 50 & 30, then we used 90 and 40 in one of our other optimizations
  - We used sigmoid and relu activation functions
    
  Were you able to achieve the target model performance?
  - We were aiming for 75% accuracy, but could only get a total of 72% accuracy. Some of our epochs were showing 74% and 75% though so with further optimization I'm sure we could have gotten there.
    
  What steps did you take in your attempts to increase model performance?
  - We tried increasing the total amount of epochs and layers, which didn't do a lot.
    
Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
  - Overall, we were close but did not quite reach the intended accuracy within three optimizations. With some additional optimizing or maybe using some other classification models, we would have reached our goal.
  - I am not exactly sure what models would be best for this exact scenario, but a couple other classification models I might look into would be KNN, & Logistic Regression.
