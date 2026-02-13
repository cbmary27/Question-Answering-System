# Introduction

The task of Question Answering (QA) in information retrieval is to answer questions intelligently using either pre-structured databases or natural language documents to provide correct answers to questions asked by humans. As opposed to a search engine which provides a list of documents as the result, a QA system presents only the requested information in a summarized and concise format. 

A major purpose of the Question Answering system (QA) is to encourage research into systems that return answers since many users prefer direct answers, and to gain experience in large-scale evaluation of QA procedures. By using natural language to answer a specific question, QA strives to satisfy users. One of the research gaps in the question answering field is that most traditional models struggle to understand contexts consisting of long sequences and the underlying relationships and dependencies present in it. In reality, systems contain large amounts of information which should be understood by question answering models to generate accurate answers for  a particular query. 

This project proposes a system to solve this by using a deep learning approach consisting of a memory network of comprising of two different models:- a unidirectional long short term memory (LSTM) and a bidirectional long short term memory (BiLSTM) for intelligent learning from a corpus consisting of question-answer pairs along with a context. Results from the experiments done on these models show that the BiLSTM based memory network model was able to understand the context better and capture relevant pieces of information when compared to the LSTM based memory network model. 

# Dataset

Used the SQuAD Dataset. See "Importing SQuAD Dataset" in code.

# Conclusion

The BiLSTM based memory network model was found to outperform the LSTM model in terms of performance in understanding the relationships between the sequences in the data. In short, the model was able to understand the context for each question and provide accurate answers. The bidirectional LSTM is used in the aforementioned analysis to create a neural network model for Q&A by integrating it with a memory network. This BiLSTM-based Q&A system is used to assess the SQuAD dataset in an all-encompassing manner.
