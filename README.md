# Proyecto Procesamiento de Lenguaje Natural -- UVG
## Summary:

There are still taboos on mental health today, and many people tend to express their problems on websites or social media. Toxic comments are a psychologically difficult subject to escalate. For this, a framework is presented to use deep learning to automatically identify and classify toxic comments into 6 identified subcategories. A bidirectional LSTM architecture will be implemented and an attempt will be made to implement an attention model to help our bidirectional LSTM. The aim is to assign weights to the categories, thus visualizing the activation of the neural network in response to each word within a sentence without losing the qualitative logic of human intuition.

---------------
Instructions
---------------

How to Train model:

1. Download and unzip glove data and place at ./data/glove/ from the following link:
   http://nlp.stanford.edu/data/glove.6B.zip
2. Download train and test data and place at ./data/ from the following link:
   https://drive.google.com/drive/folders/1sFT7priSKktVNDJW7b22y1HvjCW62T6F?usp=sharing
3. Configure experimental setup at ./experiments/run_{nn,rnn}_model.py
4. Train model and evaluate performance by running
   > cd experiments

   > python run_nn_model.py

   or 

   > python run_rnn_model.py
