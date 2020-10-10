# Music-Genre-Classification
A ML approach to find genre of a given song file.

### Requirements:
1. GTZAN Dataset. [Link.]( https://www.kaggle.com/carlthome/gtzan-genre-collection?) This dataset contains 100 songs of 10 genres each.
2. Libraries: numpy, pandas, sklearn, librosa, matplotlib

## Walk through:
The code base is written in a kaggle notebook, you create a new notebook and start working on the same just by clicking on the dataset link provided above.
There are also no need for feature extraction from all of the audio files to a dataframe, a has already been uploaded so you just need to classify the songs according to the genre by applying the algorithm you like. 
If you have some time to kill and don't fear about putting your hands into the deepest trench of MIR(Music Infromation Retreival) you can always got to this [link](https://github.com/Prakhar-FF13/Music-Genre-Classification), and understand how this feature extraction is taking place on the first hand.

As the file names says, 
> First open the [Exploring-Visualizing.ipynb](https://github.com/shrey-09/Music-Genre-Classification/blob/master/Exploring-Visualizing.ipynb) to learn about the dataset you are working on.

> Then get to know how we are using [XGBoost](https://xgboost.readthedocs.io/en/latest/python/python_api.html#module-xgboost.sklearn) to classify the songs.

> And lastly you will understand how [cosine_similarity](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.pairwise.cosine_similarity.html) works for music recommendations.
