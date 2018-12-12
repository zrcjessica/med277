# MED277

### Introduction to Biomedical Natural Language Processing Final Project \
James Sorrentino and Jessica Zhou

[Project proposal](https://docs.google.com/document/d/1CuFxbl7UYIsE8zaTxz7CsERl31eqVIJaM7aDxzFsWqU/edit?usp=sharing)

[Final project report](https://docs.google.com/document/d/1H5nZ3QRxygRVN4XT-zGZPvzfdh82XzjH0bJnDklcCZw/edit?usp=sharing)

[Final project presentation](https://docs.google.com/presentation/d/1nnD3AUv3o0FKc7B7z9bW2O10pIfAblt06K3jR8_eFbM/edit?usp=sharing)

In the `DELIVERABLES` folder can be found all of the Jupyter notebooks used to preprocess the data and train Random Forest classifiers and LSTMs for classifying sincerity of Quora questions. This project is based on the respective [Kaggle competition](https://www.kaggle.com/c/quora-insincere-questions-classification).

`FilterQuestions.ipynb` contains code for filtering questions for biomedical content and visualizing the distribution of sincere/insincere questions in the prefiltered and filtered datasets.\
`RandomForest.ipynb` contains code for preprocessing the training data, and training classifiers for both unfiltered and filtered (biomedical) questions.\
`LSTM.ipynb` contains code for preprocessing the training data and constructing the RNN for training the LSTMs for unfiltered and filtered questions.\
Run these notebooks by stepping through the cells. More detailed documentation can be found within the notebooks.

Please demo the performance of our classifiers (trained on the filtered datasets) in `LiveDemoClassifiers.ipynb`. Step through the cells, which load pickled files with preprocessed data for each respective classifier, as well as the pretrained classifiers themselves.

Required packages:
- pandas
- matplotlib
- nltk
- re
- string
- numpy
- math
- sci-kit learn
- keras 
