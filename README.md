# Enhancing Ecological Knowledge Discovery Using Large Language Models
This repository contains the codebase for my Ecosystem Analysis and Modeling Master's thesis at the University of Göttingen. 

## Overview
The field of ecology is experiencing rapid growth, resulting in a surge of scientific literature,
both contemporary and historical, spanning centuries. While this vast corpus of
text holds a wealth of knowledge, the sheer volume makes it impossible for individuals
to manually extract all the valuable insights it contains. Natural Language Processing
(NLP) emerges as a powerful solution to tackle this challenge, offering a diverse array of
applications. To accomplish this objective, we evaluate a diverse set of encoder- and encoder-decoder-based LLMs across eight distinct tasks, categorized into three domains: literature review, entity extraction and trait extraction. Overall, our findings underscore the remarkable capabilities of LLMs in
various ecological natural language processing tasks. The utilization of LLMs opens up new
horizons for efficient knowledge extraction from the extensive body of ecological literature,
offering unprecedented accuracy and productivity. As this field continues to evolve, LLMs
promise to play an increasingly pivotal role in advancing ecological research and discovery,
ultimately enhancing our understanding of the natural world and our ability to address
pressing ecological challenges.

## Installation

## Usage 
The codebase consists of jupyter notebooks divided by task:
* **Literature review**
  * **Topic modeling** - contains the code used to train and evaluate models to predict the relevance of papers to two large macroecological literature datasets.
  * **Text summarization** - contains the code used for the summarization of ecological abstracts to their titles.
* **Entity extraction**
  * **Named entity recognition** - extraction of named taxonomic entities from text.
  * **Family classification** - prediction of a species' taxonomic family from a given description.
* **Trait extraction**
  * **English categorical trait extraction** - prediction of species' categorical traits (growth form, life form) from English species' descriptions.
  * **Spanish & German categorical trait extraction** - prediction of species' categorical traits (growth form, life form) from Spanish and German species' descriptions through multilingual language models.
  * **Trait extraction in a data-deficient regime** - prediction of species' categorical traits using a small subset of English species' descriptions.
  * **Numerical trait extraction** - extraction of numerical traits using question answering language models.
 
