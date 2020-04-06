# Spam_Detection_Using_Word_Embedding
Detect Spam Messages Using Word Embedding

This kernel builds a Neural Network Model using Word Embedding (a paramount feature Natural Language Processing) to classify whether a message is Spam or not.

The Dataset consists of 5572 sentences with about 87% labelled as spam message and 13% labelled as ham.

P:S I know there is a huge class imbalance which will affect it's generalization to an unseen data, don't worry check the kernel to see how I tackle this.  

This project workflow includes:

- Loading the data
- Examining and understanding the dataset
- Preprocess the Text Data
- Building an input pipeline
- Building an Input Pipeline for the Pretrained Embedding Model
- Building an Input Data Pipeline for the Encoded Text Sequences
- Building a NN Model using a Model Subclassing API
- Training the model
- Evaluating the model using Sklearn's confusion_matrix


All these will be done with tensorflow 2.x.
