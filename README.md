# Basic-LLM
Bigram along with LSTM

In this project, I built a character-level language model using LSTM networks in PyTorch. The goal was to predict the next character in a sequence by training the model on a large English text dataset. Unlike a basic Bigram model that looks only at the previous character, my LSTM model can understand longer patterns and context, making its predictions more accurate.

I used an embedding layer to convert characters into vectors, an LSTM layer to learn from sequences, and a fully connected layer to predict the next character. I trained the model for 3000 epochs and monitored its learning using training loss graphs and label frequency plots. Through this project, I faced and solved challenges like tensor mismatches, and I gained a strong understanding of how sequence models and LSTMs work in NLP.
