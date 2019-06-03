##### Summary of Sequence to Sequence Learning with Neural Networks
* DNNs cannot be used to map sequences to sequences
*  Deep LSTM are used to encode input sequence to vector of fixed dimensionality and another deep LSTM to decode onto target sequence
*  Most likely translations are obtained using beam search
*  Reversing input sequences reduce "minimal time lag" and make learning easier
*  The model is also capable of translating very long sentences

##### Resources
* Articles & Slides
  * Stanford CS224N Seq2Seq slides - <https://web.stanford.edu/class/cs224n/slides/cs224n-2019-lecture08-nmt.pdf>
  * Stanford CS224N Seq2Seq notes - <https://web.stanford.edu/class/cs224n/readings/cs224n-2019-notes06-NMT_seq2seq_attention.pdf>
  * Interpreting, Training, and Distilling Seq2Seq Models - <http://nlp.seas.harvard.edu/seq2seq-talk/slidescmu.pdf>
  * <https://towardsdatascience.com/nlp-sequence-to-sequence-networks-part-2-seq2seq-model-encoderdecoder-model-6c22e29fd7e1>


* Videos
  * Seq2Seq Architecture - <https://www.youtube.com/watch?v=MJg7QPjlErw>
  * Seq2Seq NIPS Oral Session - <https://www.youtube.com/watch?v=-uyXE7dY5H0>
