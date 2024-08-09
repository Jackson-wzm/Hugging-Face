# Hugging-Face
https://github.com/huggingface


# Course Learn

NLP Course

What is NLP?
NLP is a field of linguistics and machine learning focused on understanding everything related to human language. The aim of NLP tasks is not only to understand single words individually, but to be able to understand the context of those words.

The following is a list of common NLP tasks, with some examples of each:

Classifying whole sentences: Getting the sentiment of a review, detecting if an email is spam, determining if a sentence is grammatically correct or whether two sentences are logically related or not
Classifying each word in a sentence: Identifying the grammatical components of a sentence (noun, verb, adjective), or the named entities (person, location, organization)
Generating text content: Completing a prompt with auto-generated text, filling in the blanks in a text with masked words
Extracting an answer from a text: Given a question and a context, extracting the answer to the question based on the information provided in the context
Generating a new sentence from an input text: Translating a text into another language, summarizing a text
NLP isn’t limited to written text though. It also tackles complex challenges in speech recognition and computer vision, such as generating a transcript of an audio sample or a description of an image.

The 🤗 Transformers library provides the functionality to create and use those shared models. The Model Hub contains thousands of pretrained models that anyone can download and use. You can also upload your own models to the Hub!

## Transformers,what can they do?

from transformers import pipeline

Some of the currently available pipelines are:
feature-extraction (get the vector representation of a text)
fill-mask
ner (named entity recognition)
question-answering
sentiment-analysis
summarization
text-generation
translation
zero-shot-classification

## How do Transformers work?

This list is far from comprehensive, and is just meant to highlight a few of the different kinds of Transformer models. Broadly, they can be grouped into three categories:

GPT-like (also called auto-regressive Transformer models)
BERT-like (also called auto-encoding Transformer models)
BART/T5-like (also called sequence-to-sequence Transformer models)


Transformers are big models
Apart from a few outliers (like DistilBERT), the general strategy to achieve better performance is by increasing the models’ sizes as well as the amount of data they are pretrained on.

Sharing language models is paramount: sharing the trained weights and building on top of already trained weights reduces the overall compute cost and carbon footprint of the community


