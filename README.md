# DEEP-LEARNING-PROJECT

"COMPANY":CODETECH IT SOLUTIONS

"NAME":Narasapuram Safin Sulthan

"INTERN ID":CT06DF620

"DOMAIN":DATA SCIENCE

"DURATION": 6 WEEKS

"MENTOR":NEELA SANTOSH

In this project, I performed sentiment analysis on IMDB movie reviews using a deep learning approach powered by Long Short-Term Memory (LSTM) networks in TensorFlow. The objective was to classify movie reviews as either positive or negative, based on the emotional content of the text. The IMDB dataset used is a well-known benchmark in NLP, providing a balanced and preprocessed corpus of 50,000 labeled movie reviews.

Workflow Overview
The project was executed through the following stages:

1. Library Imports
To build the pipeline, I relied on key Python libraries:

TensorFlow and Keras for model building and training

Pandas for data handling and exporting predictions

Matplotlib for visualizing training progress

These tools form the foundation for most modern machine learning tasks in Python.

2. Dataset Loading and Preparation
The dataset was loaded using TensorFlow’s built-in imdb module. I limited the vocabulary to the top 10,000 most frequent words, ensuring a balance between model performance and training speed. Since neural networks require consistent input sizes, all reviews were padded or truncated to a fixed length of 200 tokens.

3. Model Construction
The LSTM model was built using Keras's Sequential API. The architecture consisted of:

An Embedding layer to convert word indices into dense 32-dimensional vectors

A single LSTM layer with 64 units to capture sequential patterns and long-term dependencies in the text

A Dense output layer with a sigmoid activation function for binary classification

The model was compiled using the Adam optimizer and binary cross-entropy loss, both standard choices for classification tasks.

4. Model Training
Training was done over 5 epochs, using the .fit() method. A validation split was created using the test dataset to monitor generalization during training. The model learned to improve its predictions by minimizing the difference between its outputs and the actual sentiment labels.

5. Performance Visualization
To assess learning behavior, I plotted both training and validation accuracy over time. These graphs helped in diagnosing issues such as overfitting or underfitting and gave visual feedback on the model’s progress.

6. Making Predictions
After training, the model was used to generate predictions on the first 100 samples from the test dataset. Probabilities were converted into sentiment labels using a threshold of 0.5: predictions above this value were considered positive, and below it, negative.

7. Exporting Results
Finally, I saved the prediction results into a CSV file using Pandas. The output file contained the predicted sentiment, predicted probability, and the actual sentiment for each review, making it easier to analyze the model’s effectiveness and errors.

Conclusion
This project presents a complete deep learning pipeline for sentiment analysis on movie reviews. By leveraging the power of LSTM networks, the model captures the sequential nature and contextual dependencies of language. The result is a robust sentiment classifier capable of interpreting real-world opinions expressed in natural language. This approach can be extended to other domains such as product reviews, news analysis, or customer feedback systems.











Ask ChatGPT



<img width="640" height="480" alt="Image" src="https://github.com/user-attachments/assets/f18c6c8d-adbe-47c2-a34b-c4ea26390802" />
