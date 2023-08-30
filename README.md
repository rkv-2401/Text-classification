# Text-classification
Notebooks used in a Kaggle competition as part of UNSW coursework.

A rapid data pre-processing pipeline was built using SpaCy which was 6x faster than the conventional pre-processing pipeline. Data Augmentation was applied on this pre-processed dataset.

Using the Glove50 pre-trained embedding, we converted the input texts into numerical vectors that can be interpreted by machine learning algorithms.

We used a single CNN model along with Global Average Pooling as a regression to predict the feature scores of the text provided as input.

Then, we designed some metrics to evaluate the performance of the model and the quality of it's outputs. The plots can be found in the notebook.

### Scores - 
#### CNN w/ Augmentation - 0.61
#### Multi-input model with CNN and Dense layers - 0.59
