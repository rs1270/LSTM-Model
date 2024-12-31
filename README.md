# LSTM-Model
LSTM-Based Sentiment Analysis on IMDB Movie Reviews Dataset
Objective
Develop and evaluate an LSTM-based model to predict whether a movie review is positive or negative.
Approach
Dataset Loading
Load the IMDB dataset using TensorFlow's built-in tf.keras.datasets.imdb.
Inspect the dataset structure, observing integer-encoded words and corresponding labels.
Data Exploration
Visualize the distribution of review lengths to understand variability.
Explore label counts (positive vs. negative reviews).
Assess vocabulary size and encoding for preprocessing decisions.
Text Preprocessing
Pad sequences using TensorFlow's pad_sequences to ensure uniform input lengths.
Optionally decode reviews back into text for interpretability.
Build the LSTM Model
Use an embedding layer to transform integer-encoded words into dense vector representations.
Add LSTM layers to capture sequential dependencies and contextual sentiment.
Train the Model
Compile the model with the binary_crossentropy loss function, optimizing for binary classification.
Train the model on the training dataset and validate performance on the test dataset.
Evaluate the Model
Compute accuracy, precision, recall, and F1 score to assess the model's performance.
Make Predictions
Test the model on custom reviews.
Decode predictions to classify them as "positive" or "negative."
Results
The model achieved the following performance metrics:

Binary Cross-Entropy Loss: 13.3400
Accuracy: 0.8666
F1 Score: 0.8666
Precision: 0.8667
Recall: 0.8666
