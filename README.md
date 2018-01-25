* [Python 3](https://www.python.org/downloads/)
* [TensorFlow >= 1.4](https://www.tensorflow.org/)
* [scikit-learn](http://scikit-learn.org/)
---
#### Word Embedding（词向量）
* Skip-Gram &nbsp; &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/word2vec_skipgram.py) &nbsp; &nbsp; [Test](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/word2vec_skipgram_test.py) &nbsp; &nbsp; [Result](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/word2vec_skipgram_test.md)

* CBOW &nbsp; &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/word2vec_cbow.py) &nbsp; &nbsp; [Test](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/word2vec_cbow_test.py) &nbsp; &nbsp; [Result](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/word2vec_cbow_test.md)

#### Text Generation（文本生成）
* Char-RNN &nbsp; &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/rnn_text_gen.py) &nbsp; | &nbsp; [English Story Test](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/rnn_text_gen_test.py) &nbsp; | &nbsp; [Chinese Address Test](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/rnn_text_gen_addr_test.py)
    * Char-RNN + Beam-Search &nbsp; &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/char_rnn_beam.py) &nbsp; | &nbsp; [English Story Test](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/char_rnn_beam_test.py) &nbsp; | &nbsp; [Chinese Address Test](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/char_rnn_addr_test.py)

* CNN-Highway-RNN &nbsp; &nbsp;[Paper](https://arxiv.org/abs/1508.06615) &nbsp; &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/cnn_rnn_text_gen.py) &nbsp; &nbsp; [PTB Test](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/cnn_rnn_text_gen_test.py)

* Self-Attention &nbsp; &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/self_attn_lm.py) &nbsp; | &nbsp; [English Story Test](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/self_attn_lm_test.py) &nbsp; &nbsp; [Result](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/self_attn_lm_test.md) &nbsp; | &nbsp; [Chinese Address Test](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/self_attn_lm_addr_test.py) &nbsp; &nbsp; [Result](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/self_attn_lm_addr_test.md)

#### Text Classification（文本分类）
* CNN &nbsp; &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/concat_conv_1d_text_clf.py) &nbsp; &nbsp; [IMDB Test](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/concat_conv_1d_text_clf_imdb_test.py) &nbsp; &nbsp; [Result](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/concat_conv_1d_text_clf_imdb_test.md)

    * CNN + k-Max Pooling &nbsp; &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/kmax_conv_1d_text_clf.py) &nbsp; &nbsp; [IMDB Test](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/kmax_conv_1d_text_clf_imdb_test.py) &nbsp; &nbsp; [Result](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/kmax_conv_1d_text_clf_imdb_test.md)

* RNN &nbsp; &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/rnn_text_clf.py) &nbsp; &nbsp; [IMDB Test](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/rnn_text_clf_imdb_test.py) &nbsp; &nbsp; [Result](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/rnn_text_clf_imdb_test.md)

    * RNN + Attention &nbsp; &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/rnn_attn_text_clf.py) &nbsp; &nbsp; [IMDB Test](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/rnn_attn_text_clf_imdb_test.py) &nbsp; &nbsp; [Result](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/rnn_attn_text_clf_imdb_test.md)

#### Sequence Labelling（序列标记）
* Bi-RNN + CRF &nbsp; &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/birnn_crf_clf.py) &nbsp; &nbsp; [POS Tagging Test](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/pos_birnn_crf_test.py) &nbsp; &nbsp; [Chinese Segmentation Test](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/chseg_birnn_crf_test.py) 

* Self-Attention + CRF &nbsp; &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/multihead_attn_clf.py) &nbsp; &nbsp; [POS Tagging Test](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/multihead_attn_clf_pos_test.py) &nbsp; &nbsp; [Chinese Segmentation Test](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/multihead_attn_clf_chseg_test.py) 

#### Sequence to Sequence（序列对序列）
* Seq2Seq &nbsp; &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/seq2seq.py) &nbsp; &nbsp; [Sorting Test](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/seq2seq_test.py)

   * Seq2Seq + Attention &nbsp; &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/seq2seq_attn.py) &nbsp; &nbsp; [Sorting Test](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/seq2seq_attn_test.py) 

   * Seq2Seq + BiLSTM Encoder &nbsp; &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/seq2seq_birnn.py) &nbsp; &nbsp; [Sorting Test](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/seq2seq_birnn_test.py) 

   * Seq2Seq + Beam-Search &nbsp; &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/seq2seq_beam.py) &nbsp; &nbsp; [Sorting Test](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/seq2seq_beam_test.py) 

   * Seq2Seq + BiLSTM Encoder + Attention + Beam-Search &nbsp; &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/seq2seq_ultimate.py) &nbsp; &nbsp; [Sorting Test](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/seq2seq_ultimate_test.py) 

* Pointer Network &nbsp; &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/pointer_net.py) &nbsp; &nbsp; [Sorting Test](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tensorflow/pointer_net_test.py) 

* [Attention Is All You Need](https://github.com/zhedongzheng/finch/tree/master/nlp-models/tensorflow/attn_is_all_u_need) 

#### Question Answering（问题回答）
* [Dynamic Memory Network](https://github.com/zhedongzheng/finch/tree/master/nlp-models/tensorflow/dmn) 

#### Generative Modelling（生成式建模）
* [VAE (Variational Autoencoder)](https://github.com/zhedongzheng/finch/tree/master/nlp-models/tensorflow/vae)

   * [VAE + Discriminator](https://github.com/zhedongzheng/finch/tree/master/nlp-models/tensorflow/toward-control)

#### Reinforcement Learning（强化学习）

For this section, please install [OpenAI Gym](https://github.com/openai/gym)
* TensorFlow &nbsp; | &nbsp; Policy Gradient &nbsp; &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/nlp-models/rl-models/tensorflow/pg.py) &nbsp; &nbsp; [CartPole Test](https://github.com/zhedongzheng/finch/blob/master/nlp-models/rl-models/tensorflow/pg_cartpole_test.py)
---
#### How To Use
1. The following command clones all the files

      (it is large due to historical reasons, sorry)
   ```
   git clone https://github.com/zhedongzheng/finch.git
   ```

2. Use [contents](https://github.com/zhedongzheng/finch#contents) to find the model and test that may interest you, click on that test
   <img src="https://github.com/zhedongzheng/finch/blob/master/assets/addr_0.png" width="600">

3. Find the test file path

   <img src="https://github.com/zhedongzheng/finch/blob/master/assets/addr.png" width="600">

4. run on command line
   ```
   cd finch/nlp-models/tensorflow
   python rnn_attn_estimator_imdb_test.py
   ```
---
