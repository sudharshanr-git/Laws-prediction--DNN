# Laws-prediction--DNN

- Pre-processed data after data analysis.
- Used SentenceTransformers LLM 'LaBSE' to encode text data after reducing number of tokens without information loss by logical techniques.
- Used mean pooling technique while encoding due to resource constraints.
- Built a Deep Neural network to predict laws applicable based on the facts and considerations of the case given as input.
- DNN results on test data: 
Average Precision : 65.9%
Average Recall: 50%
Average Accuracy: 98.7%
- After multiple models trained with different architectures, it is found that the above results are due to information loss in mean pooling step.

- Currently testing Sequential models to overcome the information loss.