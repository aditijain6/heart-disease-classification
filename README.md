# heart-disease-classification

This is my first machine learning model. I try the following classification algorithms to improve my model accuracy: 

- Support Machine Classifiers
- GaussianProcessClassifier 
- KNeighborsClassifier
- RandomForestClassifier
- MultinomialNB

I may have made a mistake in the implementation of these algorithms, because they don't seem to improve the score by that much. The model accuracy was still pretty low at around 57 % , so I tried to preprocess the data using the Standard Scaler and Normalizer functions. I have yet to implement the pipeline for these and truly learn the scenario where each would be useful, but in terms of differentiating between standardization and normalization, this is what I have gathered. 

- Standardization = mean = 0 and std = 1
- Normalization: scaling and shifting so values are between 0 and 1

I would also like to figure out how to best visualize this data. I have displayed it as a scatter matrix, but I can't really find any connections, especially because the target feature are fixed integer numbers from 0 to 4, which makes the graphing strange. I will have to look into this more. 
