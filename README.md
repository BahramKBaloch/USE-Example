# USE-Example
Have you heard about Universal Sentence Encoder (USE)? 
https://tfhub.dev/google/universal-sentence-encoder/4

It can be used to solve almost all text classification problems with little effort.

Here is a notebook showing how to use it within the model but it can also be used to simply convert text (of any length) to numeric vectors (sentence embeddings) and then any classifier (SVM, decision tree, etc) can be trained on those vectors (sentence embeddings). As shown in the attached example.

https://colab.research.google.com/drive/1kdag15MYFNj8Ldyf1IzVUHC0NXbzH_SX?usp=sharing

As a bonus, I also added
Tf-serving and a trick to make API hosted on google-colab accessible externally (free GPU based server for demos ;) ).

There are many different variants of USE (https://tfhub.dev/google/collections/universal-sentence-encoder/1) some build for efficiency (USE-Lite based on Deep Averaging Network https://tfhub.dev/google/universal-sentence-encoder-lite/2), some for high accuracy (USE-Large based on transformers https://tfhub.dev/google/universal-sentence-encoder-large/5), and some built to support multiple languages in a single model (MUSE supports up to 16 languages https://tfhub.dev/google/universal-sentence-encoder-multilingual/3)

![tf docs example](https://github.com/BahramKBaloch/USE-Example/blob/main/example%20use.png?raw=true)
