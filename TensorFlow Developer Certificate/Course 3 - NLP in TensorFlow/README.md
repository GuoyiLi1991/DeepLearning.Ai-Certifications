# Course 3: Natural Language Processing in TensorFlow

## Description
In this course, you will build natural language processing systems using TensorFlow. You will learn to process text, including tokenizing and representing sentences as vectors, so that they can be input to a neural network. You’ll also learn to apply RNNs, GRUs, and LSTMs in TensorFlow. Finally, you’ll get to train an  LSTM on existing text to create original poetry!

- #### Week 1: Sentiment in text
	- The first step in understanding sentiment in text, and in particular when training a neural network to do so is the tokenization of that text. This is the process of converting the text into numeric values, with a number representing a word or a character. This week you'll learn about the Tokenizer and pad_sequences APIs in TensorFlow and how they can be used to prepare and encode text and sentences to get them ready for training neural networks!
- #### Week 2: Word Embeddings
	- Last week you saw how to use the Tokenizer to prepare your text to be used by a neural network by converting words into numeric tokens, and sequencing sentences from these tokens. This week you'll learn about Embeddings, where these tokens are mapped as vectors in a high dimension space. With Embeddings and labelled examples, these vectors can then be tuned so that words with similar meaning will have a similar direction in the vector space. This will begin the process of training a neural network to udnerstand sentiment in text -- and you'll begin by looking at movie reviews, training a neural network on texts that are labelled 'positive' or 'negative' and determining which words in a sentence drive those meanings.
- #### Week 3: Sequence models
	- In the last couple of weeks you looked first at Tokenizing words to get numeric values from them, and then using Embeddings to group words of similar meaning depending on how they were labelled. This gave you a good, but rough, sentiment analysis -- words such as 'fun' and 'entertaining' might show up in a positive movie review, and 'boring' and 'dull' might show up in a negative one. But sentiment can also be determined by the sequence in which words appear. For example, you could have 'not fun', which of course is the opposite of 'fun'. This week you'll start digging into a variety of model formats that are used in training models to understand context in sequence!
- #### Week 4: Sequence models and literature
	- Taking everything that you've learned in training a neural network based on NLP, we thought it might be a bit of fun to turn the tables away from classification and use your knowledge for prediction. Given a body of words, you could conceivably predict the word most likely to follow a given word or phrase, and once you've done that, to do it again, and again. With that in mind, this week you'll build a poetry generator. It's trained with the lyrics from traditional Irish songs, and can be used to produce beautiful-sounding verse of it's own!

---

# Certification
<p align="center">
  <img src="../DeepLearning.ai TensorFlow Developer Certification Images/Courses/Natural_Language_Processing_in_TensorFlow.jpg" | width=800 />
</p>
