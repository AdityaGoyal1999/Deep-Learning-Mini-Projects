# Word Representation and Prediction

This predicts the word given a context window of 3 previous words. The technique is 4grams.

**Preprocessing** - Preprocessing the data requires taking words and converting them according to 4gram structure. Then, each word is represented as a one-hot vector.

**Training** - The model is a Neural Network and it predicts the next word for a context window of 3 words.
