---
title: Topics & Papers
layout: default
nav_order: 3
---


# Topics & Papers

We're basically following the structure of this nice [Review of the Neural History of NLP](http://blog.aylien.com/a-review-of-the-recent-history-of-natural-language-processing/) by Sebastian Ruder. That blogpost provides a useful narrative around the individual papers that we will discuss (as well as some useful links to background resources, so be sure to read it first).

You should be able to find all of the papers just by dropping the title into the search engine of your choice. But do make sure that you actually get the version specified here. Sometimes there are conference paper versions and later journal paper versions with the same title.


## 01 Language Modelling with Neural Networks


### Feed Forward

**Main:**

Bengio, Y., Ducharme, R., Vincent, P., & Janvin, C. (2003). A Neural Probabilistic Language Model. The Journal of Machine Learning Research, 3, 1137–1155. **Selected for Week 03.**

**Background:**

Bengio, Y., Ducharme, R., & Vincent, P. (2001). A neural probabilistic language model. In NIPS. 




### Recurrent

**Main:**

Graves, A. (2013). Generating sequences with recurrent neural networks. ArXiv Preprint ArXiv:1308.0850, 1–43. **Selected for Week 04.**

**Background:**

Melis, G., Dyer, C., & Blunsom, P. (2018). On the State of the Art of Evaluation in Neural Language Models. In ICLR (pp. 1–10). 


### Background Material

* <http://karpathy.github.io/2015/05/21/rnn-effectiveness/>
* <http://colah.github.io/posts/2015-08-Understanding-LSTMs/>


## 02 Multitask Learning

**Main:**

Collobert, R., Weston, J., Bottou, L., Karlen, M., Kavukcuoglu, K., & Kuksa, P. (2011). Natural Language Processing (Almost) from Scratch. Journal of Machine Learning Research, 12, 2461–2505. 

**Background:**

Collobert, R., & Weston, J. (2008). A Unified Architecture for Natural Language Processing: Deep Neural Networks with Multitask Learning. In ICML. 


## 03 Word Representations

### word2vec

**Main:**

Mikolov, T., Chen, K., Corrado, G., & Dean, J. (2013). Efficient Estimation of Word Representations in Vector Space. In ICLR (pp. 1–12). 

**Background:**

Mikolov, T., Chen, K., Corrado, G., & Dean, J. (2013). Distributed Representations of Words and Phrases and their Compositionality. In NIPS (pp. 1–9). 

Levy, O., & Goldberg, Y. (2014). Neural Word Embedding as Implicit Matrix Factorization. In NIPS 2014 (pp. 1–9).



### multilingual

**Main:**

Ruder, S., Vulić, I., & Søgaard, A. (2017). A Survey Of Cross-lingual Word Embedding Models. ArXiv, 1–55. 


### Background Material

* <http://ruder.io/word-embeddings-1/>
* <http://ruder.io/word-embeddings-2017/>



## 04 Convolutional Networks for NLP


**Main 1:**

Kalchbrenner, N., Grefenstette, E., & Blunsom, P. (2014). A Convolutional Neural Network for Modelling Sentences. In ACL (pp. 655–665). 

**Background 1:**

Kalchbrenner, N., Espeholt, L., Simonyan, K., Oord, A. van den, Graves, A., & Kavukcuoglu, K. (2016). Neural Machine Translation in Linear Time. ArXiv. 


**Main 2:**

Kim, Y. (2014). Convolutional Neural Networks for Sentence Classification. In EMNLP. 


## 05 Trees

### Recursive NNs

**Main:**

Socher, R., Perelygin, A., Wu, J. Y., Chuang, J., Manning, C. D., Ng, A. Y., & Potts, C. (2013). Recursive Deep Models for Semantic Compositionality Over a Sentiment Treebank. In EMNLP 2013.

Tai, K. S., Socher, R., & Manning, C. D. (2006). Improved Semantic Representations From Tree-Structured Long Short-Term Memory Networks. In ACL. 


### RNN Grammars

**Main:**

Dyer, C., Kuncoro, A., Ballesteros, M., & Smith, N. A. (2016). Recurrent Neural Network Grammars. In NAACL (pp. 199–209). 

**Background:**

Kuncoro, A., Ballesteros, M., Kong, L., Dyer, C., Neubig, G., & Smith, N. A. (2017). What Do Recurrent Neural Network Grammars Learn About Syntax? In EACL (Vol. 1, pp. 1249–1258). 


## 06 Sequence to Sequence

Sutskever, I., Vinyals, O., & Le, Q. V. (2014). Sequence to Sequence Learning with Neural Networks. In NIPS 2014 (p. 9). Computation and Language; Learning. 

Gillick, D., Brunk, C., Vinyals, O., & Subramanya, A. (2016). Multilingual Language Processing From Bytes. In NAACL (pp. 1296–1306).



## 07 Attention

**Main:**

Bahdanau, D., Cho, K., & Bengio, Y. (2015). Neural Machine Translation by Jointly Learning to Align and Translate. In ICLR 2015 (pp. 1–15). 


**Main:**

Vaswani, A., & Uszkoreit, J. (2017). Attention Is All You Need. In NIPS. 


### Background Material

* <http://jalammar.github.io/illustrated-transformer/>



## 08 Memory

**Main:**

Kumar, A., Irsoy, O., Su, J., Bradbury, J., English, R., Pierce, B., … Socher, R. (2016). Ask Me Anything: Dynamic Memory Networks for Natural Language Processing. ArXiv, 48, 1–10.


## 09 What do these things learn?

**Main:**

Blevins, T., Levy, O., & Zettlemoyer, L. (2018). Deep RNNs Encode Soft Hierarchical Syntax. In ACL (pp. 14–19).


Kuncoro, A., Dyer, C., Hale, J., Yogatama, D., Clark, S., & Blunsom, P. (2018). LSTMs Can Learn Syntax-Sensitive Dependencies Well, But Modeling Structure Makes Them Better. Proceedings of the 56st Annual Meeting of the Association for Computational Linguistics, 1–11.



## 10 Sesame Street (Massive Pretraining for Word and Sentence Representations)


**Main:**

Peters, M. E., Neumann, M., Iyyer, M., Gardner, M., Clark, C., Lee, K., & Zettlemoyer, L. (2018). Deep contextualized word representations. In NAACL 2018 (pp. 2227–2237). 

Devlin, J., Chang, M.-W., Lee, K., & Toutanova, K. (2018). BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding. ArXiv. 


**Background:**

Tenney, I., Xia, P., Chen, B., Wang, A., Poliak, A., Mccoy, R. T., … Pavlick, E. (2019). What do you learn from context? Probing for sentence structure in contextualized word representations. In ICLR 2019 (pp. 1–17).

Radford, A., Wu, J., Child, R., Luan, D., Amodei, D., & Sutskever, I. (2018). Language Model and Unsupervised Multitask Learning.

### Background Material

* <http://jalammar.github.io/illustrated-bert>
* [BERT slides by lead author](https://nlp.stanford.edu/seminar/details/jdevlin.pdf)


## 11 Multitask II

Wang, A., Singh, A., Michael, J., Hill, F., Levy, O., & Bowman, S. R. (2019). GLUE: A Multi-Task Benchmark and Analysis Platform for Natural Language Understanding. In ICLR 2019 (pp. 1–20). Retrieved from 

Ruder, S., Bingel, J., Augenstein, I., & Søgaard, A. (2019). Latent Multi-task Architecture Learning. In AAAI 2019. Retrieved from 


