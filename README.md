# Fake_Reddit_Prediction

# problem definition

- The problem is about building a model to classify and detect which real news and fake news from just its titles.

- inputs: (60000) observations for a training dataset 
- output is (59151) label.

# Function and Model
Text preprocessing, Tokenization Then Vectorization on Each text, 

Then Training The Model (Classification)

# Challenges

The Data Has Unclean Text That Contain Huge Number Of Punctuations, Non-English Letters, Misspellings And Grammatical Errors. So it require an appropriate text cleaning technique to be selected.

# Model impact

Prevent The Spreading of Rumors or False News On Social Media. 

# The ideal solution

Using a SVC Classifier with GridSearch to get the best hyperparameters combinations to get better Accuracy result (86.23%)
