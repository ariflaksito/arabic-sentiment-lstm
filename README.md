# Arabic Language Opinion Mining Based on Long Short Term Memory (LSTM)

### Abstract
Arabic is one of the official languages recognized by the united nation (UN) and is widely used in the middle east, part of Asia, Africa, and other countries. Social media activity currently dominates the textual communication on the internet and potentially represents people's views about specific issues. Opinion mining is an important task to understand public opinion polarity towards an issue. Understanding public opinion leads to better decisions in many fields, such as public services or business. Language background plays a vital role in understanding opinion polarity. The variation is not only due to the vocabulary but also cultural background. The sentence is a time series signal; therefore, sequence gives a significant correlation to the meaning of the text. A recurrent neural network (RNN) is a variant of deep learning where the sequence is considered. Long-term short memory (LSTM) is an implementation of RNN with a particular gate to keep or ignore specific word signals during a sequence of input. Text is unstructured data, and it cannot be processed further by machine unless an algorithm transforms the representation into readable machine learning format in a vector of numerical value. The transformation algorithm ranging from Terms Frequency – Invers Text Frequency (TF-IDF) transform text to some advanced word Embedding. Some word embedding methods include GloVe, word2vec, BERTH, and fastText. This research experimented with those sentences to vector transformation of the Arabic text dataset. This study implements and compares GloVe and fastText word embedding algorithms and Long short-term memory (LSTM) implementations in single, double, and triple layers. Finally, this research compares their accuracy for the opinion mining Arabic dataset. It evaluates the proposed algorithm with the ASAD dataset of 55K annotated tweets in three classes. The dataset was augmented to achieve equal proportions of positive, negative, and neutral classes. According to the evaluation results, the triple layers LSTM with fastText word embedding achieves the best testing accuracy at 90,9%, surpassing all other experiment scenarios.

### Keywords
Sentiment Analysis; Opinion mining; Neural Network; LSTM; Arabic.

### Authors:
Arief Setyanto 1, Arif Laksito 2*, Fawaz Alarfaj 3*, Mohammed Alreshoodi 4, Kusrini 1, Irwan Oyong 2, Mardhiya Hayaty 2, Abdullah Alomair 3, Naif Almusallam 3 and Lilis Kurniasari
