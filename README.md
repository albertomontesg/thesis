# Temporal Activity Detection in Untrimmed Videos with Recurrent Neural Networks

This is the LaTeX document of my degree's final thesis.

### Abstract

Deep learning techniques have been proven to be a great success for tasks like object detection and classification. They have achieve huge accuracy on images but on videos where the temporal dimension is present, more new techniques are required to face task over them.

Activity classification and temporal activity location require new models which try to explode the temporal correlations the videos present to achieve good results on this tasks. The work presented try to face this tasks, for both activity classification and temporal activity localization using the ActivityNet Dataset.

This work propose to face the tasks with a two stage pipeline. The first stage is to extract video features from the C3D which exploit temporal correlations and then a RNN made up by LSTM cells which try to learn long-term correlations and returning a sequence of activities along the video that will help to classify and temporally localize activities.

### Cite

```
@mastersthesis {xMontes,
	title = {Temporal Activity Detection in Untrimmed Videos with Recurrent Neural Networks},
    author = {Montes, Alberto},
	year = {2016},
    month = {June},
	editor = {Salvador, Amaia and Giró-i-Nieto, X.}
}
```
