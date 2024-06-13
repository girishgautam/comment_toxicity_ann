#   Deep Learning Projects with Python and Keras - To detect comment toxicity level using neural netwrok

This Jupyter notebook demonstrates how to build an comment classifier using Python and TensorFlow. The classifier distinguishes between 6 types of toxicity level - 'toxic', 'severe_toxic', 'obscene', 'threat', 'insult',
       'identity_hate'

## Steps Involved

1. **Downloading data from Kaggle**
   Link - kaggle competitions download -c jigsaw-toxic-comment-classification-challenge.

2. **Building a Data Pipeline**
   - Constructed a data pipeline using TensorFlow dependencies to manage the flow of image data.

3. **Preprocessing text data'comments'**
   - Cleaned the text data using a cleaning function- remove puncutaion, remove digits, remve stopwords, made lower case, tokenised, lemmatised.
   - Vectorised the text data.

4. **Creating a Deep Neural Network Classifier**
   - Used the Sequential library from Keras to build a deep neural network (DNN) classifier.

5. **Evaluating Model Performance**
   - Assessed the model's performance using standard evaluation metrics - Precision, Recall and Accuracy.

6. **Saving the Model for Deployment**
   - Saved the trained model to a file for future deployment.

## Dependencies and Libraries Used

- **TensorFlow**: For building and training the neural network.
- **nltk**: For text processing tasks.
- **Matplotlib**: For plotting and visualisation.
- **Keras**: Specifically the Sequential API for constructing the neural network.
- **OS**: For file and directory operations.
