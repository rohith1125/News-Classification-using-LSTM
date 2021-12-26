# Make Sure you have the following packages installed
- pandas
- numpy
- matplotlib
- seaborn
- WordCloud
- re
- nltk
- warnings
- keras
- sklearn

Or simply run the requirments.txt to install all the required packages
# GloVe

## Introduction

GloVe is an unsupervised learning algorithm for obtaining vector representations for words. Training is performed on aggregated global word-word co-occurrence statistics from a corpus, and the resulting representations showcase interesting linear substructures of the word vector space.

## Getting started (Code download)

Download the [latest code](https://github.com/stanfordnlp/GloVe) (licensed under the Apache License, Version 2.0).
Look for "Clone or download"
Unpack the files:  unzip master.zip
Compile the source:  cd GloVe-master && make
Run the demo script: ./demo.sh
Consult the included README for further usage details, or ask a question

## Download pre-trained word vectors

Pre-trained word vectors. This data is made available under the Public Domain Dedication and License v1.0 whose full text can be found at: http://www.opendatacommons.org/licenses/pddl/1.0/.
Wikipedia 2014 + Gigaword 5 (6B tokens, 400K vocab, uncased, 50d, 100d, 200d, & 300d vectors, 822 MB download): glove.6B.zip
Common Crawl (42B tokens, 1.9M vocab, uncased, 300d vectors, 1.75 GB download): glove.42B.300d.zip
Common Crawl (840B tokens, 2.2M vocab, cased, 300d vectors, 2.03 GB download): glove.840B.300d.zip
Twitter (2B tweets, 27B tokens, 1.2M vocab, uncased, 25d, 50d, 100d, & 200d vectors, 1.42 GB download): glove.twitter.27B.zip
Ruby script for preprocessing Twitter data
Citing GloVe

Jeffrey Pennington, Richard Socher, and Christopher D. Manning. 2014. GloVe: Global Vectors for Word Representation. [pdf](https://nlp.stanford.edu/pubs/glove.pdf) [bib]

Download the 100 dimensional Global vectors for word representation, [Glove](https://nlp.stanford.edu/projects/glove/) which's used in the project
