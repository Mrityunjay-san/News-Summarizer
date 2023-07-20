# News Summarizer

A project where we take news articles from various news papers and summarize them in two ways, Abstractive and Extractive

Text summarization is the process of condensing a longer piece of text into a shorter version while preserving its most important information. The goal of text summarization is to provide a concise summary that captures the key points, main ideas, and relevant details of the original text.

There are two types of Summarization techniques:
<ul>
    <li>Abstractive Summarization</li>
    <li>Extractive Summarization</li>
</ul>

## Abstractive Summarization

<li>Abstractive summarization involves generating new sentences that capture the essence of the original text. 
<li>This approach goes beyond simply extracting sentences and aims to create a coherent and concise summary by understanding the meaning of the text and       paraphrasing it in a more condensed form.
<li>Abstractive summarization often involves the use of natural language processing (NLP) techniques and machine learning algorithms.
We have used T5 model for Abstractive summarization

## Extractive Summarization

<li>In this approach, the summary is created by selecting and combining the most important sentences or phrases from the original text.
<li>The sentences are usually chosen based on their relevance, importance, and informativeness.
<li>Extractive summarization does not generate new sentences but rather extracts and reorganizes existing ones.
<li>We have used pre-trained Bert model for extractive summarization

## Models

### DistilBERT

<li>DistilBERT is a variant of the popular BERT (Bidirectional Encoder Representations from Transformers) model that has been specifically designed to be smaller and faster while maintaining a similar level of performance
<li>It achieves this by using a knowledge distillation technique to transfer knowledge from a larger pre-trained model like BERT to a smaller model.

### T5

<li>T5 (Text-to-Text Transfer Transformer) is a versatile transformer-based model that can be fine-tuned for a wide range of natural language processing tasks, including abstractive newspaper summarization. 
<li>T5 is a powerful model for abstractive newspaper summarization, as it combines the benefits of pre-training on large-scale datasets, an encoder-decoder architecture, and the flexibility of fine-tuning
<li>With its PyTorch implementation, it provides an accessible and efficient solution for generating high-quality news article summaries.





