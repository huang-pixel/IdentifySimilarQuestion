# Project Analysis

## Overview

**How to use Transformer model and machine learning techniques to find the semantic identical sentences ?**

In this project, i will explore the dataset `Quora Question pairs` which is a competition topic from the community [Kaggle](https://www.kaggle.com/competitions/quora-question-pairs)[^1]. The main method is using the pre-trained model [all-MiniLM-L6-v2](https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2) hosted on the HuggingFace Model Hub[^2] to maps sentences to a 384 dimensional dense vector space, and then calculate the sentence vector based on the obtained word vector. Finally, i compute the distance of sentence vectors to predict whether the sentences pairs are semantically equals or otherwise. 

[^1]: **Kaggle**, a subsidiary of [Google LLC](https://en.wikipedia.org/wiki/Google_LLC "Google LLC"), is an online community of [data scientists](https://en.wikipedia.org/wiki/Data_science "Data science") and [machine learning](https://en.wikipedia.org/wiki/Machine_learning "Machine learning") practitioners.  


[^2]: Hugging Face, Inc. is an American company that develops tools for building applications using machine learning.
