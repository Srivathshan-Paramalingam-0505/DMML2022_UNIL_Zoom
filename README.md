# Team_zoom_coding_challenge - Training a model to compute french difficulty
*This is our way of resolving the coding challenge!*

<img width="1227" alt="Screenshot 2022-12-21 at 19 00 05" src="https://user-images.githubusercontent.com/83650518/208973150-52ec1d94-ba0f-4f34-8596-92a6e6733dad.png">


## Summary
* CSV Files
* First notebook : Project guidelines
* Second notebook : Different tokenizers
* Third notebook : Text classification using NTLK (natural language toolkit)
* References

## CSV Files
It contains provided data from the Kaggle competition
## First notebook : Project guidelines
On that part, we trained models using our raw data, without cleaning them
## Second notebook : Different tokenizers
On that notebook, we tried to tokenize using several ways, particularly with the following libraries : regular expression (re) and spacy tokenizer
## Third notebook : Text classification using Feature Extractions
On that last part, we decided to create a new DataFrame containing new features about the properties of the sentences. Once cleaned, we used the ntlk library to clean the data before training them in our models.
## References

### Main references: 
* https://scikit-learn.org/stable/index.html
* https://github.com/michalis0/DataMining_and_MachineLearning
### Other references:
* https://docs.python.org/3/howto/regex.html
* https://towardsdatascience.com/ensemble-methods-or-democracy-for-ai-bac2fa129f61
* https://datacorner.fr/nltk/
* https://medium.com/all-things-ai/in-depth-parameter-tuning-for-svc-758215394769
* https://goodboychan.github.io/python/datacamp/natural_language_processing/2020/07/15/01-Regular-expressions-and-word-tokenization.html#Introduction-to-regular-expressions
* https://github.com/madhurimamandal/Text-classification-into-difficulty-levels
