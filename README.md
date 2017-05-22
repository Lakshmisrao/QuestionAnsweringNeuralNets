# QuestionAnsweringNeuralNets

Answer prediction using Neural Nets.

A python application built using the tensor flow library. Uses Recurrent Neural Nets and LSTMs to perform a question answering task on MCTest data set. 

Concepts of Deep Learning are used to address the question answering task. The intention is to avoid the tedious task of numerous feature extraction that are done in traditional linguistic approaches. Long Short-Term Memory models are used to generate embeddings of questions and answers and we compute the distance between questions and answers pairs by measuring the cosine similarity in order to select the appropriate answer. 

Dataset used: MCTest dataset.

MCTest dataset is a free data set that has 450 stories each of which has multiple questions and the each questions has 4 choices answer choice in which one of them is correct and others are wrong.
Data cleaning & input formatting is in python and embedding generation is done using skip gram model.  The actual training using LSTM is done using Tensor Flow libraries, also in python.
