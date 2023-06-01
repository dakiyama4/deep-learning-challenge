# deep-learning-challenge

The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

We started by removing any unnecessary information and dropped the columns “EIN” and “NAME”, and the column “NAME” was added back for binning. We then split the data in training and testing sets. The target variable was named “IS_SUCCESSFUL” where yes = 1  and no = 0. “CLASSIFICATION” was used for binning and we utilized data points as a limit to bin uncommon variables together with the value of “Other” for each. We used “get_dummies” to encode categorical variables after we checked if the binning worked. 

When Neural Networks were applied, there were 3 layers for each model. 477 params were made and the first attempt had 73% accuracy. The second attempt had over 78% accuracy with almost 3,300 params and was achieved by using the “NAME” column in the dataset. We should utilize multiple layers for deep learning models because it learns how to predict and classify information based on filtering inputs through layers. 
