# AI Learning with focus on Gen AI
This document attempts to create a curated list of article, blogs, coursed to go through to learn Gen AI. I will attempt to 

## 1. Learn about attention mechanism
An Attention Mechanism is a machine learning technique that allows models to focus on relevant part of input data to improve performance. It work by assigning weights to different elements of data, based on how relevant they are to the task at hand.
Attention mechanism are particularly useful in tasks that require context, such as Machine tranlation, Text summarization, Question answering, and Image Recognition.


1. Break down the input: The model breaks down the input into smaller pieces, such as indvidual words.
2. Pick out important bits: The model compares each piece to a query or question to determine which pieces are most important
3. Assign importance: Each piece if given a score based on how well it matches the query
4. Focus attention: The model gives more attention to pieces with higher scores, and less attention to those with lower scores.
5. Put it all together: The model adds up all the pieces, giving more weight to the important ones.

Attention mechanisms are inspired by how humans focus on specific aspects of their environment. They mimic human-like selective focus, which helps neural networks process and understand complex data.

Here are a few good articles to learn about Attention Mechanism

- https://h2o.ai/wiki/attention-mechanism/
- https://machinelearningmastery.com/the-attention-mechanism-from-scratch/

## 2. Transformers vs RNNs vs LSTM/GRU
Language Processing (NLP) has become synonymous with Large Language Models (LLMs) and Generative AI. These are built using Sequence Models, which is class of Machine Learning models designed for tasks that involve sequential data, where the order of elements in the input is important. Natural 
Key sequence models are

- Recurrent Neural Networks (RNNs): were the first neural networks of their kind. They are best for tasks that involve sequential dependencies, such as speech recognition and sentiment analysis. RNNs are less compute intensive and responsive when data is fed in real-time
- Long Short-Term (LSTM) Networks: are used for tasks that requre capturing long-term dependencies, such as language modeling, speech recognition, and financial forecasting. LSTMs use a structure based on RNNs, with special `gates` that control how information is modified in a hidden cell state.
- Gated Recurrent Units (GRUs): are another type of neural network that improve on RNNs for working with textual data. GRUs receive information indirectly as a set of hidden states passed on through the input sequcen
- Transformer Models: These networks are state-of-the-art for many natual language processing tasks, such as document summarisation, machine translation, and sentiment analysis. Transformers use a self-attention mechanism to process sequential data in parallel, which allows them to process multiple words simultaneously.

For more information

- https://aiml.com/what-are-sequence-models-key-algorithms-and-their-applications/
- https://aiml.com/compare-the-different-sequence-models-rnn-lstm-gru-and-transformers/




