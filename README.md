# Text-classification
Notebooks used in a Kaggle competition as part of coursework.
A rapid data pre-processing pipeline was built using SpaCy which was 6x faster than the conventional pre-processing pipeline! 
<br/>
<img src = "https://github.com/rkv-2401/Text-classification/assets/59438748/d727ecf2-a7bd-4a90-9bc3-e2927794b41f" width = "40%">

<img src = "https://github.com/rkv-2401/Text-classification/assets/59438748/96975ed9-91dd-4d6b-bfbe-611aa5550e86" width = "40%">

Data Augmentation was applied on this pre-processed dataset.

Using the Glove50 pre-trained embedding, we converted the input texts into numerical vectors that can be interpreted by machine learning algorithms.

We used a single CNN model along with Global Average Pooling used as a regression to predict the feature scores of the text provided as input.
<br />
<img src = "https://github.com/rkv-2401/Text-classification/assets/59438748/b2695b7d-fbef-4245-a606-d74d2e0554a9" width = 40%>

We then designed some metrics to evaluate the performance of the model and the quality of it's outputs. The plots can be found in the notebook.

### Scores - 

#### kNN classification with GZip compressor for distances - 0.78
#### Baseline LSTM model - 0.646 (predicts same result for every input essay)
#### CNN w/ Augmentation - 0.61
#### Multi-input model with CNN and Dense layers - 0.59

