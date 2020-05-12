# neural_machine_translation
NMT encoder-decoder model with attention for vietnamese to english 


Based on Keras functional API to create a neural machine translation system based on the sequence-to-sequence
(seq2seq) models proposed by Sutskever et al., 2014 and Cho et al., 2014. The seq2seq
model is widely used in machine translation systems such as Google’s neural machine
translation system (GNMT) (Wu et al., 2016).


Here we will explore the seq2seq model, as well as using
attention in machine translation. The model you will implement during these two labs is
similar to the GNMT and has the potential to achieve competitive performance with the
GNMT by using larger and deeper networks.


For training and evaluating our mode we will use the English-Vietnamese parallel corpus of
TED talks provided by the ​IWSLT Evaluation Campaign​. For our tasks, we will translate from
Vietnamese into English.



Main three files:
- Main code is in nmt_model_keras.py
- The remaining two are the parallel corpus, one for English (data.30.en) and one for
Vietnamese (data.30.vi).
