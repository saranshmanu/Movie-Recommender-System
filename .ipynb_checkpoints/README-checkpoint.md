# Movie Recommender System

### Approach to the recommender system
The recommender system was creating using a Deep Learning Autoencoder approach. The model is based on a Collaborative Filtering technique where ranking of movies for the user is generated based on the ratings of some of the best movies by them. I have used a small version of MovieLens dataset to train the Neural Network for ranking system.

#### Collaborative Filtering
Collaborative Filtering is a method used by recommender systems to make predictions about an interest of an specific user by collecting taste or preferences information from many other users. The technique of Collaborative Filtering has the underlying assumption that if a user A has the same taste or opinion on an issue as the person B, A is more likely to have B’s opinion on a different issue.

#### Autoencoders
Architecturally, the form of an Autoencoder is a feedforward neural network having an input layer, one hidden layer and an output layer. The output layer has the same number of neurons as the input layer for the purpose of reconstructing it’s own inputs. This makes an Autoencoder a form of unsupervised learning, which means no labelled data are necessary — only a set of input data instead of input-output pairs.

## Resources
<ul>
<Li> <a href = "https://grouplens.org/datasets/movielens/">MovieLens dataset</a>
<Li> <a href = "https://towardsdatascience.com/deep-autoencoders-for-collaborative-filtering-6cf8d25bbf1d">Deep Autoencoders For Collaborative Filtering</a>
</ul>

## Frameworks
<ul>
<Li> Numpy
<Li> Pandas
<Li> Tensorflow
<Li> Keras
<Li> CoreMLTools
</ul>
