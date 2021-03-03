# Data-Science

#### Spotify Song Suggester API

- [Product Vision Document](https://docs.google.com/document/d/1LnAeTMPiyoDOr_WhCDBgnm--AFyRnsOspLgMVkamS08/edit)
- [Plotly Dash](https://lambdaschool.github.io/ds/unit2/dash-template/)
- [Kaggle Dataset](https://www.kaggle.com/tomigelo/spotify-audio-features)
- [Data Science Rubric](https://www.notion.so/Data-Science-Unit-4-814c17e421334cd8b3d2867d1d49f541)

### Project Details

 #### *Background*

> Create an algorithm to recommend songs based on user input songs. In production, Spotify uses a mixture of Deep Learning, Collaborative Filtering, persistent user 'taste profiles', frequent itemset mining, and some sort of neighbors algorithm based on
taste profiles, time listened, etc. Competitor Pandora has hired musiciologists to work on their 'music genome project' which
is probably more of a feature engineering thing using domain experts.

#### *We chose this model because:*

We ended up using only Nearest Neighbors. While we found several research papers on using
Neural Networks, LSTMs on Nearest Neighbors, we were unable to find source code or pre-trained models.

Research into siamese network matching algorithms looks more promising as they train much faster but we were also unable
to create or find a ready to use model. Also Siamese networks scale much better than Nearest Neighbors as the
dataset increases in size.


Read more [here: K-Nearest Neighbors](https://towardsdatascience.com/machine-learning-basics-with-the-k-nearest-neighbors-algorithm-6a6e71d01761) &  [here: K-Nearest Neighbors Documentation](https://scikit-learn.org/stable/modules/neighbors.html)


#### *Our Goal:*

> **Pitch**: Build an app to enable users to browse and visualize audio features of over 116k spotify songs.

MVP: User can search for a specific song and see its audio features displayed in a visually appealing way. The app also identifies songs with similar audio features.
DS:
1. Build a model to recommend songs based on similarity to user input (I like song x, here are n songs like it based on these similar features)
2. Create visualizations using song data to highlight similarities and differences between recommendations.

