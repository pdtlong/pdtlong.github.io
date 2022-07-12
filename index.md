# Portfolio
---
## Natural Language Processing
### [NLP] Building a Part of Speech Tagger (POS) Using Viterbi
[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/pdtlong/English-PosTag-Prediction-Using-VIterbi)

**This is my completed project about POS Tagging** __*Achieved over 95% accuracy*__

**Part-of-Speech** (POS) *(noun, verb, and preposition)* can help in understanding the meaning of a text by identifying how different words are used in a sentence. POS can reveal a lot of information about neighbouring words and syntactic structure of a sentence.

**The Hidden Markov Models (HMM)** is a statistical model for modelling generative sequences characterized by an underlying process generating an observable sequence.

*POS tagging using Hidden Markov Models (HMMs)* which are *probabilistic sequence models*.



<center><img src="images/postag.png" width="550"/></center>

---
### [NLP] Building a Transition Based Dependency Parsing

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/pdtlong/Transition-Based-Dependency-Parsing)

**Transition-based dependency parsing**: is a fast and effective approach for dependency parsing. Traditionally, a transitionbased dependency parser processes an input sentence and predicts a sequence of parsing actions in a left-to-right manner.

Successfully built a complete model with detailed running steps. You can refer to the details in the code section, Model currently has 45 Postags, 94084 tokens and total 349 dependency arcs

<center><img src="images/dependency.png" width="550"/></center>

---

### [NLP] Evaluation of the quality of word embedding models for Vietnamese (GloVe, Word2Vec, ELMO, FASTTEXT)

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/pdtlong/Word-Embedding-Models-for-Vietnamese-GloVe-Word2Vec-ELMO-FASTEXT)

**This is a research project that got a highest score in my and a friend's natural language processing course on evaluating the quality of Word embeddings models for Vietnamese.**

The main task focuses on **evaluating the quality of Words Embedding models** Including: **GloVe, Word2Vec, ELMO, FASTTEXT**

To ensure fairness for the evaluation process. The model will be passed 2 criteria: 
- **Accuracy scores**
- **Convergence speed when training through loss**

In addition, the evaluation process also takes place on **4 different models:**

<center><img src="images/wordembedding_comparison.png" width="550"/></center>

*The chart describes in detail the accuracy measured on the test set of the embedding sets on each classification model*

<center><img src="https://user-images.githubusercontent.com/55480300/178413854-49f5b2e9-371f-455d-8671-1e299b9c0479.png" width="550"/></center>

*Example Graph of loss function of word-embedding models compared from 1st model MLPs (custom)*

---
### [NLP] Deep Text Abtractive Summarization of Vietnamese news using GAN

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/pdtlong/Text-Abtractive-Summarization-Using-GAN)

**Abstractive Text Summarization**: is the task of generating a short and concise summary that captures the salient ideas of the source text. The generated summaries potentially contain new phrases and sentences that may not appear in the source text

Within the scope of this project, I do it on *crawled data from Vietnamese news stories and label them as empty news* (the news has been summarized by the station).

<center><img src="images/Text-Summarization-Abstractive.png" width="550"/></center>


---

### [NLP] Building a Vietnamese Language model with Tensorflow (keras)
[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/pdtlong/Vietnamese-Languages-model_keras)

**A Vietnamese language model**: is a probabilistic statistical model that determines the probability of a given sequence of words occurring in a sentence based on the previous words. It helps to predict which word is more likely to appear next in the sentence.

*This is a model built for the purpose of understanding the structure of the language model. So will not focus on accuracy (because the dataset is small under 10k words)**

<center><img src="images/VLM.gif" width="550"/></center>

---
## Computer Vision & Digital Image Processing
### [CV & DIP] Building an OCR to Extract Info from Identity Cards

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/pdtlong/English-PosTag-Prediction-Using-VIterbi)

This is an integrated system of **advanced image processing methods in image preprocessing** and the application of ** Tesseract (Open Source OCR Engine)**.
Gives about *90-92% accuracy manually evaluated on 300 images*

**The current model has the following functions:**
- Adjust the size and drag the 4 sides perpendicularly even when taking photos at an angle (no more than 45 degrees)
- Self-recognize both sides of an ID card (new and old model)
- Crop the part of the photo containing the information (text) on the identity card
- Extract identifiable information into text

<center><img src="images/ocr.gif" width="550"/></center>

---
### [DIP] Adaptive Thresholding using the Integral Image
[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/pdtlong/English-PosTag-Prediction-Using-VIterbi)
<center><img src="images/viterbi1.png" width="500"/></center>



