# Natural Language Processing Assignments

Welcome to the hands-on assignments for our course on NLP concepts. These assignments are designed to give you practical experience with core concepts, helping you explore the nuances and challenges in natural language processing.

## Assignment 1: Curse of Dimensionality Experiment

### Description
This assignment explores the concept of the **curse of dimensionality** in language representation. You will create one-hot encodings for words in a dataset and compare them to word embeddings to understand the practical implications of high-dimensional representations.

### Dataset
- **[20 Newsgroups Dataset](https://scikit-learn.org/0.19/datasets/twenty_newsgroups.html):** Contains approximately 20,000 newsgroup documents, organized across 20 categories, suitable for generating word encodings and analyzing vocabulary size.
- **[SMS Spam Collection Data](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset):** Smaller dataset with text messages labeled as spam or ham, which allows exploration of word encoding on shorter text.

### Steps
1. Load and preprocess the dataset, including tokenizing the text.
2. Create one-hot encodings for the words in the dataset, observing the high dimensionality.
3. Compute and discuss memory usage of the one-hot encodings for various vocabulary sizes.
4. Compare this with pre-trained word embeddings (such as GloVe or Word2Vec) for the same text to observe the dimensionality reduction and benefits of dense embeddings.

### Follow-Up Questions
- Why does the curse of dimensionality pose a challenge in natural language processing?
- How do dense embeddings improve computational efficiency compared to one-hot encoding?
- Are there trade-offs when switching from one-hot encoding to dense word embeddings?

---

## Assignment 2: Creating a Markov Chain Text Generator

### Description
In this assignment, you will create a **simple text generator using Markov Chains**. You’ll train a model on a text dataset, create bigram or trigram chains, and generate new text sequences to observe how realistic they can become.

### Dataset
- **[The Adventures of Sherlock Holmes](https://www.kaggle.com/datasets/andrewmvd/sherlock-holmes-corpus):** A single-text corpus that’s rich in vocabulary and structure.
- **[Shakespeare’s Complete Works](https://www.kaggle.com/datasets/kingburrito666/shakespeare-plays):** Offers structured text with dialogues, suitable for sequence modeling and generating responses.

### Steps
1. Load and preprocess the dataset, focusing on tokenizing and lowercasing words.
2. Create a bigram or trigram Markov Chain based on word sequences.
3. Generate new text by randomly selecting transitions based on the chain’s probabilities.
4. Experiment with different starting words or phrases to see how the generated text changes.

### Follow-Up Questions
- How does the chain length (unigram, bigram, trigram) affect the coherence of generated text?
- What are the limitations of Markov Chains in generating human-like text?
- What improvements might you suggest to make the generated text more realistic?

---

## Assignment 3: Building and Evaluating a Simple Chatbot

### Description
In this assignment, you will create a basic rule-based **chatbot** using a Markov Chain model trained on text conversations. This chatbot will respond to simple queries based on word patterns and sequences in the text. Test its “human-like” qualities by having others interact with it and give feedback.

### Dataset
- **[Cornell Movie Dialogues Dataset](https://www.kaggle.com/datasets/rajathmc/cornell-movie-dialogs-corpus):** Contains dialogue snippets from movies, ideal for conversational modeling.
- **[Persona-Chat Dataset](https://huggingface.co/datasets/personachat):** A conversational dataset with various dialogue examples, good for creating chat patterns.

### Steps
1. Load and preprocess the dataset, structuring it as a series of dialogue exchanges.
2. Use a bigram or trigram Markov Chain to model response sequences based on user inputs.
3. Implement simple keyword matching to improve response relevance.
4. Test the chatbot’s responses by interacting with it and making adjustments to improve coherence.

### Follow-Up Questions
- How well does the chatbot handle ambiguous or complex questions?
- How might you modify this chatbot to make it more adaptable to different conversation topics?
- What are the ethical implications of deploying simplistic chatbots in real-world scenarios?

---

### Conclusion

These assignments will give you practical experience with critical NLP concepts, including dimensionality, language generation with Markov Chains, and the basics of conversational modeling. Good luck, and enjoy exploring these foundational topics in NLP!
