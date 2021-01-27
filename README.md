# Summarize-Text-with-Machine-Learning

Types of Approaches to Summarize Text
Before I dive into showing you how we can summarize text using machine learning and python, it is important to understand what are the types of text summarization to understand how the process works, so that we can use logic while using machine learning techniques to summarize the text.

Generally, Text Summarization is classified into two main types: Extraction Approach and Abstraction Approach. Now let’s go through both these approaches before we dive into the coding part.

The Extractive Approach
The Extractive approach takes sentences directly from the document according to a scoring function to form a cohesive summary. This method works by identifying the important sections of the text cropping and assembling parts of the content to produce a condensed version.

The Abstractive Approach
The Abstraction approach aims to produce a summary by interpreting the text using advanced natural language techniques to generate a new, shorter text – parts of which may not appear in the original document, which conveys the most information.

In this article, I will be using the extractive approach to summarize text using Machine Learning and Python. I will use the TextRank algorithm which is an extractive and unsupervised machine learning algorithm for text summarization.
